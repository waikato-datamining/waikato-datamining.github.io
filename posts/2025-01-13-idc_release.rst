.. title: image-dataset-converter release
.. slug: 2025-01-13-idc-release
.. date: 2025-01-13 09:31:00 UTC+13:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text

A new release of our `image-dataset-converter-all <https://github.com/waikato-datamining/image-dataset-converter-all>`__ library
is now available: **0.0.6**. Docker images have been deployed as well.

The most notably changes are:

* using 90% as default quality for JPEG images now as a good compromise between quality and size (PIL uses 75% by default),
  this can be overridden with environment variable `IDC_JPEG_QUALITY`
* added methods to idc.api module: `jpeg_quality()`, `array_to_image(...)`, `empty_image(...)`
* numpy is limited to <2.0.0 to avoid issues with the imgaug library
