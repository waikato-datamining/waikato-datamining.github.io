.. title: Expertise
.. slug: expertise
.. date: 2024-11-20 10:34:00 UTC+13:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text


Spectral data analysis
======================

.. thumbnail:: /images/methods.png
   :alt: Comparison of spectral data analysis methods
   :align: right

For more than fifteen years, we have developed and deployed software that takes advantage
of machine learning models to predict properties of plant and soil samples, using spectra
from various instruments: near-infrared (`NIR <https://en.wikipedia.org/wiki/Near-infrared_spectroscopy>`__),
mid-infrared (MIR), laser-incuded breakdown spectroscopy (`LIBS <https://en.wikipedia.org/wiki/Laser-induced_breakdown_spectroscopy>`__)
and X-ray fluorescence (`XRF <https://en.wikipedia.org/wiki/X-ray_fluorescence>`__).

For decades, many organizations have relied on global methods like partial least squares
regression(`PLS <https://en.wikipedia.org/wiki/Partial_least_squares_regression>`__) for
their modeling. However, global methods do not perform well with complex data derived
from, for instance, soil samples. From the start, our software took advantage of locally
weighted learning, achieving much better results.

In recent years, we have been able to push the boundaries even further, by adopting
advanced modeling techniques using `deep learning <https://en.wikipedia.org/wiki/Deep_learning>`__.

Our commercial `S3000 software <link://slug/s3000>`__ can not only be used for building models
on your data, but also for integrating into your business processes.


Hyperspectral imaging
=====================

.. thumbnail:: /images/happy_viewer.png
   :alt: Viewer interface of the HAPPy tools
   :align: right

The last few years, we have been expanding our expertise to hyperspectral imaging (`HSI <https://en.wikipedia.org/wiki/Hyperspectral_imaging>`__)
as well. After the `School of Engineering <https://www.waikato.ac.nz/about/faculties-schools/engineering/>`__
purchased a `hyperspectral camera <https://hsi.eng.waikato.ac.nz/hardware/>`__, we developed a Python-based
suite of tools called `HAPPy <https://hsi.eng.waikato.ac.nz/happy/>`__ (*Hyperspectral Application Platform in Python*)
for annotating and processing their data.

On the one hand, the suite contains graphical tools that allow viewing of the captured data, as
well as annotating the images (either using polygons or on a pixel-level). On the other hand, you
have the ability to define and run command-line pipelines over your data to allow for repeatable
data conversions and model building (using `scikit-learn <https://scikit-learn.org/>`__ or
`Keras <https://keras.io/>`__).



Image processing
================

.. thumbnail:: /images/objdet.png
   :alt: Object detection of cars
   :align: right

With the advent of frameworks like `Tensorflow <https://en.wikipedia.org/wiki/TensorFlow>`__
and `PyTorch <https://en.wikipedia.org/wiki/PyTorch>`__, deep learning techniques became
more accessible. Many cutting edge algorithms and libraries have complex dependencies that
not only interfer with each other, but also change frequently. These libraries are often
geared towards academic experimentation and not production-ready. By employing containerization
offered by `Docker <https://en.wikipedia.org/wiki/Docker_(software)>`__ and custom extensions,
we are able to deploy these frameworks in production environments (for training and inference).

We have extensive experience in the following areas:

* image classification
* object detection
* instance segmentation
* image segmentation


Natural language processing
===========================

.. thumbnail:: /images/asr.png
   :alt: Automatic speech recognition
   :align: right

`OpenAI <https://openai.com/>`__ pushed the envelop with their `ChatGPT <https://chatgpt.com/>`__
models and how models can chat naturally with humans. Only very few organizations are in a position
nowadays to build such large language models (LLMs), as they require not only huge amounts of
data but also massive hardware (`Meta's Llama 3.1 was trained on 16,000 H100 GPUs <https://ai.meta.com/blog/meta-llama-3-1/>`__).
However, a lot of these models can be used locally and, if necessary, further fine-tuned.
Smaller variants of the models, which are still very capable, can even be run on consumer-grade hardware.
That way, you can make sure that your data stays local and confidential (`data sovereignty <https://en.wikipedia.org/wiki/Data_sovereignty>`__).

We can work with you in the following domains:

* automatic speech recognition
* small and large language models (SLMs/LLMs)
