.. title: gifr release
.. slug: 2023-11-03-gifr-release
.. date: 2023-11-03 14:0:00 UTC+13:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text

A lot of our Docker images allow the user to make predictions in two ways: using simple
file-polling or via a `Redis <https://redis.io/>`__ backend. File-polling is great for
testing, but unsuitable for a production system due to wear-and-tear on SSDs.

Initially, I developed a really simple library for sending and receiving data via Redis,
called *simple-redis-helper*:

`https://github.com/fracpete/simple-redis-helper <https://github.com/fracpete/simple-redis-helper>`__

With this library you get some command-line tools for broadcasting, listening, etc. Sufficient
for someone who is comfortable with the command-line (or especially when logged in remotely
via terminal), but not so great for your clients.

Now, there is the brilliant `gradio <https://www.gradio.app/>`__ library that was specifically
developed for such scenarios: to create easy to use and great looking interfaces for your machine
learning models.

The last couple of days, I have put together a new library that is tailored to our Docker images
called *gifr*:

`https://github.com/waikato-datamining/gifr <https://github.com/waikato-datamining/gifr>`__

With the first release, the following types of models are supported:

- image classification
- image segmentation
- object detection/instance segmentation
- text generation
