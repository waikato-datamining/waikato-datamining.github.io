.. title: SpeciesNet 4.0.1 Docker images available
.. slug: 2025-03-05-speciesnet-docker
.. date: 2025-03-05 13:21:00 UTC+13:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text


First Docker images are available for the `SpeciesNet <https://github.com/google/cameratrapai>`__
network that `Google announced on March 3rd, 2025 <https://blog.google/outreach-initiatives/entrepreneurs/ai-nature-climate-accelerator-nonprofits-speciesnet/>`__:

* `CUDA 12.1 <https://github.com/waikato-datamining/speciesnet/tree/main/4.0.1_cuda12.1>`__
* `CPU <https://github.com/waikato-datamining/speciesnet/tree/main/4.0.1_cpu>`__

Below is an example on how to use these images (on Linux or on Windows under WSL2).

Prerequisites:

* create a directory for your output eg "speciesnet"
* in that directory create the following sub-directories

  * cache
  * config
  * data
  * output

Processing data:

* copy the images that you want to analyze into the "speciesnet/data" directory
* from the "speciesnet" directory launch the appropriate docker image in interactive mode

  * CPU::

        docker run --rm --gpus=all --shm-size 8G --net=host \
          -u $(id -u):$(id -g) -e USER=$USER \
          -v `pwd`:/workspace \
          -v `pwd`/cache:/.cache \
          -v `pwd`/config:/.config \
          -v `pwd`/cache:/.torch \
          -it waikatodatamining/speciesnet:4.0.1_cpu

  * CUDA::

        docker run --rm --gpus=all --shm-size 8G --net=host \
          -u $(id -u):$(id -g) -e USER=$USER \
          -v `pwd`:/workspace \
          -v `pwd`/cache:/.cache \
          -v `pwd`/config:/.config \
          -v `pwd`/cache:/.torch \
          -it waikatodatamining/speciesnet:4.0.1_cuda21.1

* run the following script to process your images::

    speciesnet_run_model \
        --folders "/workspace/data" \
        --predictions_json "/workspace/output/predictions.json"

Or, if you want to run the individual steps separately::

  speciesnet_run_model --detector_only \
      --folders "/workspace/data" \
      --predictions_json "/workspace/output/detections.json"
  speciesnet_run_model --classifier_only \
      --folders "/workspace/data" \
      --detections_json "/workspace/output/detections.json" \
      --predictions_json "/workspace/output/classifications.json"
  speciesnet_run_model --ensemble_only \
      --folders "/workspace/data" \
      --detections_json "/workspace/output/detections.json" \
      --classifications_json "/workspace/output/classifications.json" \
      --predictions_json "/workspace/output/predictions.json"

On your host system, the "speciesnet/output" directory will then contain the generated .json file(s), with
"predictions.json" containing all the relevant information (classification and bbox).

For more information on the json output format:

`https://github.com/google/cameratrapai/tree/main?tab=readme-ov-file#output-format <https://github.com/google/cameratrapai/tree/main?tab=readme-ov-file#output-format>`__
