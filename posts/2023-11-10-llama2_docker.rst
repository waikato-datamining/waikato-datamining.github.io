.. title: Llama-2 Docker images available
.. slug: 2023-11-10-llama2-docker
.. date: 2023-11-10 16:33:00 UTC+13:00
.. tags: release
.. category: docker
.. link: 
.. description: 
.. type: text

Llama-2, despite `not actually being open-source as advertised <https://blog.opensource.org/metas-llama-2-license-is-not-open-source/>`__,
is a very powerful large language model (LLM), which can also be fine-tuned with custom data. With
version `v0.0.3 <https://github.com/waikato-llm/llm-dataset-converter/releases/tag/v0.0.3>`__
of our `llm-dataset-converter <https://github.com/waikato-llm/llm-dataset-converter>`__ Python library,
it is now possible to generate data in `jsonlines <https://jsonlines.org/>`__ format that the new
`Docker images <https://github.com/waikato-llm/huggingface_transformers/tree/master/4.31.0_cuda11.7_llama2>`__
for Llama-2 can consume:

* In-house registry:

  * ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-huggingface-transformers:4.31.0_cuda11.7_llama2``

* Docker hub:

  * ``waikatodatamining/pytorch-huggingface-transformers:4.31.0_cuda11.7_llama2``

Of course, you can use these Docker images in conjunction with our `gifr <link://slug/2023-11-03-gifr-release>`__
Python library for `gradio <https://www.gradio.app/>`__ interfaces as well (`gifr-textgen`).
