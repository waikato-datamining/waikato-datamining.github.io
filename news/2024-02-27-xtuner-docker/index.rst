.. title: XTuner Docker images available
.. slug: 2024-02-27-xtuner-docker
.. date: 2024-02-27 16:40:00 UTC+13:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text

`XTuner <https://github.com/InternLM/xtuner>`__ is an efficient, flexible and full-featured toolkit for fine-tuning
large models (InternLM, Llama, Baichuan, Qwen, ChatGLM) and released under the Apache 2.0 license. The advantage
of this framework is that it is not tied down to a specific LLM architecture, but supports multiple ones out of the box.
With the just released version `v0.2.0 <https://github.com/waikato-llm/llm-dataset-converter/releases/tag/v0.2.0>`__
of our `llm-dataset-converter <https://github.com/waikato-llm/llm-dataset-converter>`__ Python library,
you can read and write the XTuner JSON format (and apply the usual filtering, of course).

Here are the newly added image tags:

* In-house registry:

  * ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-xtuner:2024-02-19_cuda11.7``

* Docker hub:

  * ``waikatodatamining/pytorch-xtuner:2024-02-19_cuda11.7``

Of course, you can use these Docker images in conjunction with our `gifr <link://slug/2023-11-03-gifr-release>`__
Python library for `gradio <https://www.gradio.app/>`__ interfaces as well (`gifr-textgen`). Just now we released
version 0.0.4 of the library, which is more flexible in regards to text generation: it can now support send and receive
the conversation history and also parse JSON responses.
