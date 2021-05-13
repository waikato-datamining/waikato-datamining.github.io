.. title: Expertise
.. slug: expertise
.. date: 2019-10-01 10:00:00 UTC
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text


Spectral data analysis
======================

Over the last fifteen years, we have developed and deployed software that takes advantage of machine learning models to predict
properties of plant and soil samples, using spectra from various instruments: near-infrared (`NIR <https://en.wikipedia.org/wiki/Near-infrared_spectroscopy>`__), mid-infrared (MIR), laser-incuded breakdown spectroscopy (`LIBS <https://en.wikipedia.org/wiki/Laser-induced_breakdown_spectroscopy>`__) and X-ray fluorescence (`XRF <https://en.wikipedia.org/wiki/X-ray_fluorescence>`__). 

For decades, many organizations have relied on global methods like partial least squares regression(`PLS <https://en.wikipedia.org/wiki/Partial_least_squares_regression>`__) for their modeling. However, global methods do not perform well with complex data derived
from, for instance, soil samples. From the start, our software took advantage of locally weighted learning, achieving much better results.

In recent years, we have been able to push the boundaries even further, by adopting advanced modeling techniques using `deep learning <https://en.wikipedia.org/wiki/Deep_learning>`__.

.. image:: /images/methods.png
   :scale: 25
   :alt: Comparison of methods


Image processing
================

With the advent of  frameworks like `Tensorflow <https://en.wikipedia.org/wiki/TensorFlow>`__ and `PyTorch <https://en.wikipedia.org/wiki/PyTorch>`__, deep learning techniques became more accessible. Many cutting edge algorithms and libraries have complex dependencies that not only interfer with each other, but also change frequently. These libraries are often geared towards academic experimentation and not production-ready. By employing containerization offered by `Docker <https://en.wikipedia.org/wiki/Docker_(software)>`__ and custom extensions, we are able to deploy these frameworks in production environments (for training and inference).

We have experience in the following areas:

* image classification
* object detection
* image segmentation
