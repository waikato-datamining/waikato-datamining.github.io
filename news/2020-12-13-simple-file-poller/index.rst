.. title: simple-file-poller library released
.. slug: 2020-12-13-simple-file-poller
.. date: 2020-12-13 09:43:00 UTC+13:00
.. tags: release
.. category: library
.. link: 
.. description: 
.. type: text

The **simple-file-poller** Python 3 library has been released this week:

`github.com/waikato-datamining/simple-file-poller <https://github.com/waikato-datamining/simple-file-poller>`__

This library is aimed at Python projects that perform continuous processing
of files, e.g., deep learning models that locate objects in images. These
projects typically pick up files from one directory, make predictions, 
write the output in some format to another directory and then either
move the input files to the output directory or simply delete them.

Instead of having to write this code for polling and moving over and over
again, the **simple-file-poller** library allows you to plug in your
file processing code via a function that you supply to a **Poller**
object. Furthermore, you can also supply a function that can check whether
files are valid and can be processed (e.g., image files).

The **Poller** class supports two polling modes: time-based and watchdog-based.
The former waits for a specifie number of seconds between polls (if there 
were no files present). This simple approach can be used when the file
processing is not time critical. The latter approach watches the input directory
for files being created and then reacts to that immediately. This approach
allows for very low latency processing, especially useful for processing 
pipelines.

Another feature is the ability to write any output to a temporary directory
first, before moving it into the output directory. This avoids race conditions
with other processes that further process the generated output files, as the
files are guaranteed to have been fully written.

The following frameworks make use of the **simple-file-poller** now (and more will follow):

* `image-segmentation-keras <https://github.com/waikato-datamining/tensorflow/tree/master/image-segmentation-keras>`__
* `mmdetection <https://github.com/waikato-datamining/mmdetection>`__

