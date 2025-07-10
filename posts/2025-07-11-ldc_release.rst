.. title: llm-dataset-converter release
.. slug: 2025-07-11-ldc-release
.. date: 2025-07-11 09:20:00 UTC+12:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text

Version **0.2.7** of our `llm_dataset_converter <https://github.com/waikato-llm/llm-dataset-converter>`__ library has
been release. New release of ldc_doc, ldc_docx, ldc_faster_whisper, ldc_google, ldc_openai, ldc_pdf and ldc_tint
have been made available as well.

The meta-library that combines all the libraries now stands at version **0.0.6**:

`llm-dataset-converter-all <https://github.com/waikato-llm/llm-dataset-converter-all>`__

A new Docker image is available as well:

`https://hub.docker.com/r/waikatodatamining/llm-dataset-converter/tags <https://hub.docker.com/r/waikatodatamining/llm-dataset-converter/tags>`__

This release is mostly a maintenance release, but still had some useful additions:

* added `set-placeholder` filter for dynamically setting (temporary) placeholders at runtime
* added `remove-strings` filter that just removes sub-strings
* added `strip-strings` filter for stripping whitespaces from start/end of strings
