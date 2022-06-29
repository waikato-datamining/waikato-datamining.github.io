.. title: Docker Hub images
.. slug: docker-images-dockerhub
.. date: 2022-06-10 13:40:00 UTC+12:00
.. tags: docker
.. category: software
.. link: 
.. description: 
.. type: text


The following images are available from `Docker Hub <https://hub.docker.com/u/waikatodatamining>`__:


Image classification
--------------------

* PyTorch (using our `wai.pytorchimageclass <https://pypi.org/project/wai.pytorchimageclass/>`__ Python library)

  * `PyTorch 1.6.0, CUDA 10.1 <https://github.com/waikato-datamining/pytorch/tree/master/image-classification/docker/1.6.0>`__

    ``waikatodatamining/pytorch-image-classification:1.6``

  * `PyTorch 1.6.0, CPU <https://github.com/waikato-datamining/pytorch/tree/master/image-classification/docker/1.6.0_cpu>`__

    ``waikatodatamining/pytorch-image-classification:1.6_cpu``

* Tensorflow (using our `wai.tfimageclass <https://pypi.org/project/wai.tfimageclass/>`__ Python library)

  * `Tensorflow 1.14, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/image_classification/docker/1.14>`__

    ``waikatodatamining/tf_image_classification:1.14``

  * `Tensorflow 1.14, CPU <https://github.com/waikato-datamining/tensorflow/tree/master/image_classification/docker/1.14_cpu>`__

    ``waikatodatamining/tf_image_classification:1.14_cpu``

* Tensorflow (using our `wai.tflite_model_maker <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker>`__ Python library)

  * `2.4.3, CUDA 11.0 <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3>`__

    ``waikatodatamining/tflite_model_maker:2.4.3``

  * `2.4.3, CPU <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3_cpu>`__

    ``waikatodatamining/tflite_model_maker:2.4.3_cpu``


Object detection
----------------

* PyTorch/MMDetection

  * `MMDetection 2020-03-01, PyTorch 1.3 and CUDA 10.1 <https://github.com/waikato-datamining/mmdetection/tree/master/2020-03-01>`__

    ``waikatodatamining/mmdetection:2020-03-01``

  * `MMDetection 2.16.0, PyTorch 1.6 and CUDA 10.1 <https://github.com/waikato-datamining/mmdetection/blob/master/2.16.0>`__

    ``waikatodatamining/mmdetection:2.16.0``

  * `MMDetection 2.16.0, PyTorch 1.9 and CUDA 11.1 <https://github.com/waikato-datamining/mmdetection/blob/master/2.16.0_cuda11.1>`__

    ``waikatodatamining/mmdetection:2.16.0_cuda11.1``

  * `MMDetection 2.16.0, PyTorch 1.9 and CPU <https://github.com/waikato-datamining/mmdetection/blob/master/2.16.0_cpu>`__

    ``waikatodatamining/mmdetection:2.16.0_cpu``

  * `MMDetection 2.18.1, PyTorch 1.9 and CUDA 11.1 <https://github.com/waikato-datamining/mmdetection/blob/master/2.18.1_cuda11.1>`__

    ``waikatodatamining/mmdetection:2.18.1_cuda11.1``

  * `MMDetection 2.18.1, PyTorch 1.9 and CPU <https://github.com/waikato-datamining/mmdetection/blob/master/2.18.1_cpu>`__

    ``waikatodatamining/mmdetection:2.18.1_cpu``

* Tensorflow

  * `Tensorflow 1.14, Object Detection API 2019-08-31, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/object_detection/1.14.0_2019-08-31>`__

    ``waikatodatamining/tf_object_detection:1.14.0_2019-08-31``

* Tensorflow (using our `wai.tflite_model_maker <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker>`__ Python library)

  * `2.4.3, CUDA 11.0 <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3>`__

    ``waikatodatamining/tflite_model_maker:2.4.3``

  * `2.4.3, CPU <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3_cpu>`__

    ``waikatodatamining/tflite_model_maker:2.4.3_cpu``

* PyTorch/Yolov5

  * `Yolov5 2022-01-21, CPU <https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-01-21_cpu>`__

    ``waikatodatamining/pytorch-yolov5:2022-01-21_cpu``

  * `Yolov5 2022-01-21, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-01-21_cuda11.1>`__

    ``waikatodatamining/pytorch-yolov5:2022-01-21_cuda11.1``

  * `Yolov5 2022-05-31, CPU <https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-05-31_cpu>`__

    ``waikatodatamining/pytorch-yolov5:2022-05-31_cpu``

  * `Yolov5 2022-05-31, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-05-31_cuda11.1>`__

    ``waikatodatamining/pytorch-yolov5:2022-05-31_cuda11.1``


Image segmentation
------------------

* Tensorflow/Keras

  * `image-segmentation-keras 0.3.0, Tensorflow 1.14, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/image-segmentation-keras/1.14.0_0.3.0>`__

    ``waikatodatamining/image-segmentation-keras:1.14.0_0.3.0``

* PyTorch

  * `Segmentation Models 0.2.1, PyTorch 1.9.0, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/segmentation_models/0.2.1>`__

    ``waikatodatamining//segmentation_models:0.2.1``

  * `MMSegmentation 0.25.0, PyTorch 1.9 and CUDA 11.1 <https://github.com/waikato-datamining/mmsegmentation/blob/master/0.25.0_cuda11.1>`__

    ``waikatodatamining/mmsegmentation:0.25.0_cuda11.1``

  * `MMSegmentation 0.25.0, PyTorch 1.9 and CPU <https://github.com/waikato-datamining/mmsegmentation/blob/master/0.25.0_cpu>`__

    ``waikatodatamining/mmsegmentation:0.25.0_cpu``


Instance segmentation
---------------------

* PyTorch/Detectron2

  * `Detectron2 0.3, PyTorch 1.6, CUDA 10.1 <https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.3>`__

    ``waikatodatamining/detectron2:0.3``

  * `Detectron2 0.5, PyTorch 1.9, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.5>`__

    ``waikatodatamining/detectron2:0.5``

  * `Detectron2 0.6, PyTorch 1.9, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.6>`__

    ``waikatodatamining/detectron2:0.6``

* PyTorch/YOLACT++

  * `YOLACT++ 2020-02-11, PyTorch 1.2, CUDA 10.0 <https://github.com/waikato-datamining/yolact/tree/master/yolactpp-2020-02-11>`__

    ``waikatodatamining/yolactpp:2020-02-11``

* Tensorflow/Object Detection API

  * `Tensorflow 1.14, Object Detection API 2019-08-31, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/object_detection/1.14.0_2019-08-31>`__

    ``waikatodatamining/tf_object_detection:1.14.0_2019-08-31``

