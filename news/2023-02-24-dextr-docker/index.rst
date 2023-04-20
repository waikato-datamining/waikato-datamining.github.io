.. title: DEXTR Docker images available
.. slug: 2023-02-24-dextr-docker
.. date: 2023-02-24 14:35:00 UTC+13:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text

Docker images for `DEXTR <https://github.com/Britefury/dextr>`__ (Deep Extreme Cut) are now available.

DEXTR is a great tool for aiding a human annotating images for image segmentation, as it can determine
a relatively good outline of an object based on just four extreme points. Pre-trained models are available,
but custom ones (for specific domains) can be trained as well.

The code used by the docker images is available from here:

`github.com/waikato-datamining/pytorch/tree/master/dextr <https://github.com/waikato-datamining/pytorch/tree/master/dextr>`__

The tags for the images are as follows:

* In-house registry:

  * ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-dextr:0.1.2_cuda11.1``
  * ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-dextr:0.1.2_cpu``

* Docker hub:

  * ``waikatodatamining/pytorch-dextr:0.1.2_cuda11.1``
  * ``waikatodatamining/pytorch-dextr:0.1.2_cpu``
