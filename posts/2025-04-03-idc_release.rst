.. title: image-dataset-converter release
.. slug: 2025-04-03-idc-release
.. date: 2025-04-03 10:23:00 UTC+13:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text

A new release of our `image-dataset-converter-all <https://github.com/waikato-datamining/image-dataset-converter-all>`__ library
is now available: **0.0.11**. Docker images have been deployed as well.

The most notably changes since 0.0.7 are:

* support for placeholders is now available for readers/writers, which can be used in constructing input/output
  files/folders, including predefined ones available (`{CWD}`, `{HOME}`, `{TMP}`), input-based ones
  (e.g., `{INPUT_PATH}`, `{INPUT_NAMEEXT}`), user-defined ones (supplied to tools, e.g., via the `-p/--placeholders`
  option of the `idc-convert` tool) and run-time ones (set with the `set-placeholder` filter)
* added the `--resume_from` option to applicable readers, which allows resuming the pipeline from the
  file matching the supplied glob, e.g., `*/012345.jpg`
* the new `from-multi` reader and `to-multi` writer simplify the combining of datasets (from potentially
  different formats) and output in multiple formats respectively
* writers that can split the incoming stream into subsets had the new `--split_group` option added, which
  allows keeping samples together within subsets using a regular expression, e.g., when dealing with
  images that were split into sub-grids or augmented with flipping/rotating
