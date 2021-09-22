.. title: Detectron2 0.5 Docker image available
.. slug: 2021-09-22-detectron2-docker
.. date: 2021-09-22 16:06:00 UTC+12:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text

A new Docker image for building models with version 0.5 of `Detectron2 <https://github.com/facebookresearch/detectron2>`__ is available:

More information on the Docker image is available from Github:

`github.com/waikato-datamining/pytorch/tree/master/detectron2/0.5 <https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.5>`__

This CUDA 10.2 based image supersedes the 0.4 version, as that image was never used in production.

Unfortunately, CUDA 11.1 is still not possible to use (and therefore cannot run on a 3090 Ti) due
to a, so far, unresolved `bug in PyTorch <https://github.com/facebookresearch/detectron2/issues/2837>`__.
