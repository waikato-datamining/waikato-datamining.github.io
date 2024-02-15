.. title: Text classification support
.. slug: 2024-02-15-text-classification-support
.. date: 2024-02-15 16:46:00 UTC+13:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text

Large language models (LLMs) for chatbots are all the rage at the moment, but there is plenty of scope of simpler
tasks like text classification. Requiring less resources and being a lot faster is nice as well.

We turned the `HuggingFace example <https://huggingface.co/docs/transformers/v4.36.1/en/tasks/sequence_classification>`__
for sequence classification into a docker image to make it easy for building such classification models.

* In-house registry:

  * ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-huggingface-transformers:4.36.0_cuda11.7_classification``

* Docker hub:

  * ``waikatodatamining/pytorch-huggingface-transformers:4.36.0_cuda11.7_classification``

Our `gifr <https://github.com/waikato-datamining/gifr>`__
Python library for `gradio <https://www.gradio.app/>`__ received an interface for text
classification (`gifr-textclass`) in version 0.0.3.

The `llm-dataset-converter <https://github.com/waikato-llm/llm-dataset-converter>`__ library
obtained native support for text classification formats with version 0.1.1.
