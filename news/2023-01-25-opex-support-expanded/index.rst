.. title: OPEX support expanded
.. slug: 2023-01-25-opex-support-expanded
.. date: 2023-01-25 16:45:00 UTC+13:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text

Historically, our object detection frameworks have been outputting predictions in a
`CSV-based format <https://github.com/waikato-ufdl/wai-annotations-roi>`__ when
doing predictions that involved file-polling (a format that was originally derived from
`CNTK <https://learn.microsoft.com/en-us/cognitive-toolkit/>`__). Recent additions
of frameworks (and all Redis-based predictions), however, are using the
`OPEX format <https://github.com/WaikatoLink2020/objdet-predictions-exchange-format>`__
instead (a JSON-based format). In order to standardize the output of our Docker
images further, the following images now offer outputting the predictions in OPEX format
as well:

* MMDetection 2.27.0 (CPU and CUDA 11.1)
* Detectron2 0.6
* Yolov7 2022-10-08 (CPU and CUDA 11.1)
