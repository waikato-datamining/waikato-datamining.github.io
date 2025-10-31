.. title: image-dataset-converter release
.. slug: 2025-10-31-idc-release
.. date: 2025-10-31 15:45:00 UTC+13:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text

A new release of our `image-dataset-converter-all <https://github.com/waikato-datamining/image-dataset-converter-all>`__ library
is now available: **0.1.0**. Docker images have been deployed as well.

This release represents a major overhaul under the hood and lots of new functionality has been added as well.
With this release it is now possible to write more complex/integrated/reactive pipelines with the added I/O and
email plugins.

The most notably changes since 0.0.12 are:

* a new release of `seppl` allows for filters that support m-to-n not just 1-to-1 conversions
* added `list-to-sequence` stream filter that forwards list items one by one
* common code among the image-dataset-converter, audio-dataset-converter and spectral-data-converter libraries
  has been extracted and moved into separate libraries to reduce duplication: `kasperl`, `kasperl_redis`
* the new `kasperl_plots` library adds basic support for terminal plots (textual and graphical) and matplotlib ones
* the filters `tee`, `trigger` and `sub-process` support conditional execution based on meta-data evaluations now,
  as well as loading their sub-pipeline from a file to break up large pipelines into smaller, logical chunks
* added `block`, `stop` filters for controlling the flow of data (via meta-data conditions)
* the `idc-exec` tool now uses all trailing arguments as the pipeline to execute multiple times rather than as a single
  argument to a flag; alternatively, the pipeline can be loaded from a file
* the `idc-convert` tool can load a pipeline from a file now as well
* added the `text-file` and `csv-file` generators that work off files to populate the variable(s)
* the readers `from-grayscale-dp`, `from-indexed-png-is`, `from-blue-channel-is` and `from-grayscale-is` now 
  support reading only the annotations
* added `from-text-file` reader and `to-text-file` writer
* added a number of I/O related plugins: `list-files`, `move-files`, `delete-files`, `copy-files`, `watch-dir`
* added email support with `get-email` reader and `send-email` writer
* added `console` writer for outputting the data on stdout that is coming through
* added `count-specks` filter that adds counts of small objects to meta-data
* added support for caching plugins via `IDC_CLASS_CACHE` environment variable
* added `is-to-od` filter that generates object detection annotations from contours determined in image segmentation layers
* added `to-metadata` writer that outputs the meta-data of an image
* added `attach-metadata` filter that loads meta-data from a directory and attaches it to the data passing through
* added `load-data` filter to turn file names into data containers
* added `annotation-to-storage` and `annotation-from-storage` filters
* added `delete-storage` filter for removing objects from internal storage
* annotation data is now being type-checked when setting it
