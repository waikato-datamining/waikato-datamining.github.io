.. title: Yolov5 Docker images available
.. slug: 2022-11-25-yolov5-docker
.. date: 2022-11-25 10:19:00 UTC+13:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text


Docker images for the latest `Yolov5 <https://github.com/ultralytics/yolov5>`__ code base are now available.
Apart from using a newer codebase, these images now support instance segmentation as well, not just object detection.

The code used by the docker images is available from here:

`github.com/waikato-datamining/pytorch/tree/master/yolov5 <https://github.com/waikato-datamining/pytorch/tree/master/yolov5>`__

The tags for the images are as follows:

* In-house registry:

  * ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-yolov5:2022-11-05_cuda11.1``
  * ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-yolov5:2022-11-05_cpu``

* Docker hub:

  * ``waikatodatamining/pytorch-yolov5:2022-11-05_cuda11.1``
  * ``waikatodatamining/pytorch-yolov5:2022-11-05_cpu``

The new tutorial on *instance segmentation* is available from here:

`www.data-mining.co.nz/applied-deep-learning/instance_segmentation/yolov5/ <https://www.data-mining.co.nz/applied-deep-learning/instance_segmentation/yolov5/>`__
