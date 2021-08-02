.. title: Docker for Data Scientists website launched
.. slug: 2021-07-02-docker-for-data-scientists
.. date: 2021-07-02 11:00:00 UTC+12:00
.. tags: website
.. category: docker
.. link: 
.. description: 
.. type: text

Deep learning has opened a lot of new avenues in many domains for data scientists. 
However... The pain and suffering in setting up environments with the correct versions of CUDA, cuDNN, 
numpy and the actual deep learning framework is, unfortunately, all too real. Replicating an
existing test environment on a production server can prove challenging.
For quite some time now, we resorted to using docker to ease the pain of reproducing the same setup
on various servers for running experiments. Docker will not solve the problem of having to figure 
out the right combination of libraries, but at least you can easily reuse docker images and build pipelines
with frameworks that would otherwise have conflicting requirements in terms of libraries.

Long story short: in order to make it easier for data scientists to start their journey with docker,
we compiled a little `mkdocs <https://www.mkdocs.org/>`__ website:

`www.data-mining.co.nz/docker-for-data-scientists/ <https://www.data-mining.co.nz/docker-for-data-scientists/>`__

On this website, you will learn the docker basics and find also steps for creating (and using) a docker image 
that uses PyTorch's image classification facilities.

The website's source code is available from github and released under `CC-BY-SA 4.0 <https://github.com/waikato-datamining/docker-for-data-scientists/blob/main/LICENSE>`__:

`https://github.com/waikato-datamining/docker-for-data-scientists <https://github.com/waikato-datamining/docker-for-data-scientists>`__
