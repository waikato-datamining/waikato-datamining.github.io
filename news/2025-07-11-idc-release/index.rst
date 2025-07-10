.. title: image-dataset-converter release
.. slug: 2025-07-11-idc-release
.. date: 2025-07-11 10:23:00 UTC+12:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text

A new release of our `image-dataset-converter-all <https://github.com/waikato-datamining/image-dataset-converter-all>`__ library
is now available: **0.0.12**. Docker images have been deployed as well.

The most notably changes since 0.0.11 are:

* dropped numpy<2.0.0 restriction
* added grayscale-to-binary filter
* fix: sort-pixels, rgb-to-grayscale filters
* the rename filter now supports lower/upper case placeholders of name and extension as well
* requiring seppl>=0.2.17 now for skippable plugin support and avoiding deprecated use of pkg_resources
* added any-to-rgb filter for turning binary/grayscale images back into RGB ones
* added label-to-metadata filter for transferring labels into meta-data
* added metadata-to-placeholder filter for transferring meta-data into placeholders
* added basic support for images with associated depth information: DepthData, DepthInformation
* added depth-to-grayscale filter for converting depth information to grayscale image
* added depth information readers from-grayscale-dp, from-numpy-dp, from-csv-dp and from-pfm-dp
* added depth information writers to-grayscale-dp, to-numpy-dp, to-csv-dp and to-pfm-dp
* added apply-ext-mask filter to applying external PNG masks to image containers (image and/or annotations)
* added apply-label-mask filter for applying image segmentation label masks to their base images
* added label-present-ic and label-present-is that ensure that certain label(s) are present or otherwise discard the image
* filter label-present was renamed to label-present-od but keeping label-present as alias for the time being
* fix: imgseg_to_bluechannel, imgseg_to_indexedpng and imgseg_to_grayscale now handle overlapping pixels correctly, no longer adding them up and introducing additional labels
* discard-by-name filter can use names of files in specified paths now as well
* fixed the construction of the error messages in the pyfunc reader/filter/writer classes
