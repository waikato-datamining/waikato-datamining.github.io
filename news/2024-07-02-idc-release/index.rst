.. title: image-dataset-converter release
.. slug: 2024-07-02-idc-release
.. date: 2024-07-02 09:56:00 UTC+12:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text

Our `image-dataset-converter <https://github.com/waikato-datamining/image-dataset-converter>`__ library keeps evolving
and, apart from fixing bugs, we also keep adding useful stuff.

The version of the `image-dataset-converter-all` library stands now at **0.0.3**.

Since version 0.0.2 the following changes occurred:

* image-dataset-converter (core library):

  * switched to the `fast-opex` library
  * helper method `from_indexedpng` was using incorrect label index (off by 1)
  * `Data.save_image` method now ensures that source/target files exist before calling `os.path.samefile`
  * requiring seppl>=0.2.6 now
  * readers now support default globs, allowing the user to just specify directories as input (and the default glob gets appended)
  * the `to-yolo-od` writer now has an option for predefined labels (for enforcing label order)
  * the `to-yolo-od` writer now stores the labels/labels_cvs files in the respective output folders rather than using an absolute file name
  * the bluechannel/grayscale/indexed-png image segmentation readers/writers can use a value other than 0 now for the background
  * `split` filter has been renamed to `split-records`

* image-dataset-converter-imgaug: added `find-contours` filter for turning blobs in image segmentation annotations into object detection polygons.
* image-dataset-converter-imgvis:  added `add-center-overlay-od` overlay filter
* image-dataset-converter-pdf (new module): adds support for PDF, like extracting images from PDF and compiling PDF from images
