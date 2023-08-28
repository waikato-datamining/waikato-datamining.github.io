.. title: Segment-Anything in High Quality Docker images available
.. slug: 2023-08-28-sam-hq-docker
.. date: 2023-08-28 15:16:00 UTC+12:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text

Docker images for `Segment-Anything in High Quality <https://github.com/SysCV/sam-hq>`__ (SAM-HQ) are now available.

Just like `SAM <link://slug/2023-04-20-sam-docker>`__, SAM-HQ is a great tool for aiding a human annotating images for image segmentation or object detection, as it can determine
a relatively good outline of an object based on either a point or a box. Only pre-trained models are available.

The code used by the docker images is available from here:

`github.com/waikato-datamining/pytorch/tree/master/segment-anything-hq <https://github.com/waikato-datamining/pytorch/tree/master/segment-anything-hq>`__

The tags for the images are as follows:

* In-house registry:

  * ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-sam-hq:2023-08-17_cuda11.6``
  * ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-sam-hq:2023-08-17_cpu``

* Docker hub:

  * ``waikatodatamining/pytorch-sam-hq:2023-08-17_cuda11.6``
  * ``waikatodatamining/pytorch-sam-hq:2023-08-17_cpu``
