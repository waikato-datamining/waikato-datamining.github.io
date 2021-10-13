.. title: Docker images
.. slug: docker-images
.. date: 2021-10-06 16:03:00 UTC+13:00
.. tags: docker
.. category: software
.. link: 
.. description: 
.. type: text


For our own projects, we make a lot of use of `Docker <https://www.docker.com/>`__, to better manage
the varying (and often clashing) requirements for CUDA and Python libraries. We not only offer a quick
introduction to `docker for data scientists <https://www.data-mining.co.nz/docker-for-data-scientists/>`__,
but we also make (most of) our Docker images freely available (see below).

Registry
--------

In order to access these images, you need to log in our in-house registry using **public** credentials:


``docker login -u public -p public public.aml-repo.cms.waikato.ac.nz:443``


Image classification
--------------------

* PyTorch (using our `wai.pytorchimageclass <https://pypi.org/project/wai.pytorchimageclass/>`__ Python library)

  * `PyTorch 1.6.0, CUDA 10.1 <https://github.com/waikato-datamining/pytorch/tree/master/image-classification/docker/1.6.0>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/image-classification:1.6``

  * `PyTorch 1.6.0, CPU <https://github.com/waikato-datamining/pytorch/tree/master/image-classification/docker/1.6.0_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/image-classification:1.6_cpu``

* Tensorflow (using our `wai.tfimageclass <https://pypi.org/project/wai.tfimageclass/>`__ Python library)

  * `Tensorflow 1.14, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/image_classification/docker/1.14>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/image_classification:1.14``

  * `Tensorflow 1.14, CPU <https://github.com/waikato-datamining/tensorflow/tree/master/image_classification/docker/1.14_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/image_classification:1.14_cpu``

* Tensorflow (using our `wai.tflite_model_maker <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker>`__ Python library)

  * `2.4.3, CUDA 11.0 <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tflite_model_maker:2.4.3``

  * `2.4.3, CPU <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tflite_model_maker:2.4.3_cpu``


Object detection
----------------

* PyTorch/MMDetection

  * `MMDetection 2020-03-01, PyTorch 1.3 and CUDA 10.1 <https://github.com/waikato-datamining/mmdetection/tree/master/2020-03-01>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmdetection:2020-03-01``

  * `MMDetection 2.16.0, PyTorch 1.6 and CUDA 10.1 <https://github.com/waikato-datamining/mmdetection/blob/master/2.16.0>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmdetection:2.16.0``

  * `MMDetection 2.16.0, PyTorch 1.9 and CUDA 11.1 <https://github.com/waikato-datamining/mmdetection/blob/master/2.16.0_cuda11.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmdetection:2.16.0_cuda11.1``

* Tensorflow

  * `Tensorflow 1.14, Object Detection API 2019-08-31, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/object_detection/1.14.0_2019-08-31>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/object_detection:1.14.0_2019-08-31``

* Tensorflow (using our `wai.tflite_model_maker <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker>`__ Python library)

  * `2.4.3, CUDA 11.0 <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3>`__

    `public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tflite_model_maker:2.4.3`

  * `2.4.3, CPU <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3_cpu>`__

    `public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tflite_model_maker:2.4.3_cpu`


Image segmentation
------------------

* Tensorflow/Keras

  * `Tensorflow 1.14, image-segmentation-keras 0.3.0, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/image-segmentation-keras/1.14.0_0.3.0>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/image-segmentation-keras:1.14.0_0.3.0``


Instance segmentation
---------------------

* PyTorch/Detectron2

  * `Detectron2 0.3, PyTorch 1.6, CUDA 10.1 <https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.3>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/detectron2:0.3``

  * `Detectron2 0.5, PyTorch 1.9, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.5>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/detectron2:0.5``

* PyTorch/YOLACT++

  * `YOLACT++ 2020-02-11, PyTorch 1.2, CUDA 10.0 <https://github.com/waikato-datamining/yolact/tree/master/yolactpp-2020-02-11>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/yolact/yolactpp:2020-02-11``

* Tensorflow/Object Detection API

  * `Tensorflow 1.14, Object Detection API 2019-08-31, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/object_detection/1.14.0_2019-08-31>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/object_detection:1.14.0_2019-08-31``

