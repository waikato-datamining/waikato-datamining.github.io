.. title: BitNet Docker image available
.. slug: 2025-04-30-bitnet-docker
.. date: 2025-04-30 16:59:00 UTC+12:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text


First Docker image is available for Microsoft's `BitNet <https://github.com/microsoft/BitNet>`__ small language
model (SLM):

* `CPU <https://github.com/waikato-llm/bitnet/blob/main/2025-04-30_cpu>`__

Below is an example on how to use these images (on Linux or on Windows under WSL2).

Prerequisites:

* create a directory for your models and output eg "bitnet"
* in that directory create the following sub-directories

  * cache
  * triton
  * models
  * logs

Interacting with the language model:

* from the "bitnet" directory launch the docker image in interactive mode::

    docker run --shm-size 8G --net=host \
        -u $(id -u):$(id -g) -e USER=$USER \
        -v `pwd`:/workspace \
        -v `pwd`/cache:/.cache \
        -v `pwd`/triton:/.triton \
        -it waikatodatamining/bitnet:2025-05-30_cpu

* as a one-off, download the *BitNet-b1.58-2B-4T* model from within the Docker container::

    huggingface-cli download microsoft/BitNet-b1.58-2B-4T-gguf \
        --local-dir /workspace/models/BitNet-b1.58-2B-4T


* once the model is in place, you can interact with with it::

    bitnet_run_inference \
        -m /workspace/models/BitNet-b1.58-2B-4T/ggml-model-i2_s.gguf \
        -p "You are a helpful assistant" \
        -n 1024 \
        -cnv
