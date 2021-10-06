.. title: tflite model maker tools
.. slug: 2021-10-06-tflite-model-maker
.. date: 2021-10-06 16:02:00 UTC+13:00
.. tags: release
.. category: library
.. link: 
.. description: 
.. type: text


Tensorflow made the `tflite model maker <https://www.tensorflow.org/lite/guide/model_maker>`__ available a while go,
which (according to the project website) *simplifies the process of training a TensorFlow Lite model using custom
dataset. It uses transfer learning to reduce the amount of training data required and shorten the training time.*

But instead of falling back on scripting Python again, we pulled code from the their example notebooks into
a library that offers command-line utilies and published it on `PyPI <https://pypi.org/>`__ to avoid having to
write Python code over and over again for every new problem/dataset. It also makes it easy to create docker
images from it, making it highly reusable.

* `tflite_model_maker project page <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker>`__
* `GPU docker image <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3>`__
* `CPU docker image <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3_cpu>`__
