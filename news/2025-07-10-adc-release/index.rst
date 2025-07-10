.. title: audio-dataset-converter release
.. slug: 2025-07-10-adc-release
.. date: 2025-07-10 13:07:00 UTC+12:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text

A new release of our `audio-dataset-converter <https://github.com/waikato-llm/audio-dataset-converter>`__
library and it various additional dependent libraries is out.

The meta-library that combines all the libraries now stands at version **0.0.3**:

`audio-dataset-converter-all <https://github.com/waikato-llm/audio-dataset-converter-all>`__

A new Docker image is available as well:

`https://hub.docker.com/r/waikatodatamining/audio-dataset-converter/tags <https://hub.docker.com/r/waikatodatamining/audio-dataset-converter/tags>`__

Notable changes:

* improved support for placeholders via the `set-placeholder` and `metadata-to-placeholder` filters
* added `from-multi` and `to-multi` for combining multiple readers/writers
* added the `--resume_from` option to readers to allow resuming the processing from a specific file
* added the `--split_group` option ti writers: a regular expression with a single group used for keeping
  items in the same split, e.g., for identifying the base name of a file or the ID
