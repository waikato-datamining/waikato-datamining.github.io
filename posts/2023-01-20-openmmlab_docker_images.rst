.. title: OpenMMLab Docker images
.. slug: 2023-01-20-openmmlab-docker-images
.. date: 2023-01-20 13:30:00 UTC+13:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text

New year, new docker images! This time, we have refreshed our docker images that
use libaries from the `OpenMMLab <https://github.com/open-mmlab>`__ group:

* MMClassification 0.25.0 (CPU and CUDA 11.1)
* MMSegmentation 0.30.0 (CPU and CUDA 11.1)
* MMDetection 2.27.0 (CPU and CUDA 11.1)

All frameworks now offer a script (`*_onnx`) to export a PyTorch model to ONNX.

MMDetection now also allows you to select the CUDA device to train on rather
than just always using the first available GPU.
