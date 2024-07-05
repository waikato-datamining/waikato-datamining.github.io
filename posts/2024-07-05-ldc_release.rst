.. title: llm-dataset-converter release
.. slug: 2024-07-05-ldc-release
.. date: 2024-07-05 13:02:00 UTC+12:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text

Version 0.2.4 of our `llm-dataset-converter <https://github.com/waikato-llm/llm-dataset-converter>`__ library is now available.

This release is a only minor release, mainly fixing batch processing and offering default globs for readers.
The support for default globs means that the user only has to supply the directory, i.e., in a bash shell it is no
longer required to double quote the input to avoid bash expansion. Additional libraries had support for default globs
added as well where appropriate.

The `llm-dataset-converter-all <https://github.com/waikato-llm/llm-dataset-converter-all>`__ meta-library now stands at version 0.0.2.
