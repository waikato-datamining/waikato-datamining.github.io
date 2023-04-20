.. title: Segment-Anything Model Docker images available
.. slug: 2023-04-20-sam-docker
.. date: 2023-04-20 14:35:00 UTC+13:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text

Docker images for `Segment-Anything Model <https://ai.facebook.com/research/publications/segment-anything/>`__ (SAM) are now available.

SAM is a great tool for aiding a human annotating images for image segmentation or object detection, as it can determine
a relatively good outline of an object based on either a point or a box. Only pre-trained models are available.

The code used by the docker images is available from here:

`github.com/waikato-datamining/pytorch/tree/master/segment-anything <https://github.com/waikato-datamining/pytorch/tree/master/segment-anything>`__

The tags for the images are as follows:

* In-house registry:

  * ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-sam:2023-04-16_cuda11.1``
  * ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-sam:2023-04-16_cpu``

* Docker hub:

  * ``waikatodatamining/pytorch-sam:2023-04-16_cuda11.1``
  * ``waikatodatamining/pytorch-sam:2023-04-16_cpu``
