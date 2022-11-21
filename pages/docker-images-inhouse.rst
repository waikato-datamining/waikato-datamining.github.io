.. title: In-house Docker images
.. slug: docker-images-inhouse
.. date: 2022-09-30 13:13:00 UTC+13:00
.. tags: docker
.. category: software
.. link: 
.. description: 
.. type: text


In order to access these images from our `in-house registry <https://aml-repo.cms.waikato.ac.nz/#browse/browse:docker-public>`__,
you need to log in using the following credentials:

``docker login -u public -p public public.aml-repo.cms.waikato.ac.nz:443``

When pulling images, you need to ensure that you are using the following prefix (the pull commands do not show this,
due to using a reverse proxy):

``public.aml-repo.cms.waikato.ac.nz:443/``

For some of the frameworks, we have tutorials available on how to use them in practice. This includes data
preparation, training and making predictions.

`https://www.data-mining.co.nz/applied-deep-learning/ <https://www.data-mining.co.nz/applied-deep-learning/>`__


Image classification
--------------------

* PyTorch (using our `wai.pytorchimageclass <https://pypi.org/project/wai.pytorchimageclass/>`__ Python library)

  * `PyTorch 1.6.0, CUDA 10.1 <https://github.com/waikato-datamining/pytorch/tree/master/image-classification/docker/1.6.0>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-image-classification:1.6``

  * `PyTorch 1.6.0, CPU <https://github.com/waikato-datamining/pytorch/tree/master/image-classification/docker/1.6.0_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-image-classification:1.6_cpu``

* PyTorch/MMClassification

  * `MMClassification 0.23.1, PyTorch 1.9 and CUDA 11.1 <https://github.com/waikato-datamining/mmclassification/blob/master/0.23.1_cuda11.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmclassification:0.23.1_cuda11.1``

  * `MMClassification 0.23.1, PyTorch 1.9 and CPU <https://github.com/waikato-datamining/mmclassification/blob/master/0.23.1_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmclassification:0.23.1_cpu``

* Tensorflow (using our `wai.tfimageclass <https://pypi.org/project/wai.tfimageclass/>`__ Python library)

  * `Tensorflow 1.14, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/image_classification/docker/1.14>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tf_image_classification:1.14``

  * `Tensorflow 1.14, CPU <https://github.com/waikato-datamining/tensorflow/tree/master/image_classification/docker/1.14_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tf_image_classification:1.14_cpu``

* Tensorflow (using our `wai.tflite_model_maker <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker>`__ Python library)

  * `2.4.3, CUDA 11.0 <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tflite_model_maker:2.4.3``

  * `2.4.3, CPU <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tflite_model_maker:2.4.3_cpu``

* Tensorflow (using the `make_image_classifier <https://github.com/tensorflow/hub/tree/master/tensorflow_hub/tools/make_image_classifier>`__ Python library)

  * `2.9.1, CUDA 11.1 <https://github.com/waikato-datamining/tensorflow/tree/master/image_classification2/2.9.1_cuda11.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tf_image_classification2:2.9.1_cuda11.1``

  * `2.9.1, CPU <https://github.com/waikato-datamining/tensorflow/tree/master/image_classification2/2.9.1_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tf_image_classification2:2.9.1_cpu``


Object detection
----------------

* PyTorch/MMDetection

  * `MMDetection 2020-03-01, PyTorch 1.3 and CUDA 10.1 <https://github.com/waikato-datamining/mmdetection/tree/master/2020-03-01>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmdetection:2020-03-01``

  * `MMDetection 2.16.0, PyTorch 1.6 and CUDA 10.1 <https://github.com/waikato-datamining/mmdetection/blob/master/2.16.0>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmdetection:2.16.0``

  * `MMDetection 2.16.0, PyTorch 1.9 and CUDA 11.1 <https://github.com/waikato-datamining/mmdetection/blob/master/2.16.0_cuda11.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmdetection:2.16.0_cuda11.1``

  * `MMDetection 2.16.0, PyTorch 1.9 and CPU <https://github.com/waikato-datamining/mmdetection/blob/master/2.16.0_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmdetection:2.16.0_cpu``

  * `MMDetection 2.18.1, PyTorch 1.9 and CUDA 11.1 <https://github.com/waikato-datamining/mmdetection/blob/master/2.18.1_cuda11.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmdetection:2.18.1_cuda11.1``

  * `MMDetection 2.18.1, PyTorch 1.9 and CPU <https://github.com/waikato-datamining/mmdetection/blob/master/2.18.1_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmdetection:2.18.1_cpu``

  * `MMDetection 2.24.1, PyTorch 1.9 and CUDA 11.1 <https://github.com/waikato-datamining/mmdetection/blob/master/2.24.1_cuda11.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmdetection:2.24.1_cuda11.1``

  * `MMDetection 2.24.1, PyTorch 1.9 and CPU <https://github.com/waikato-datamining/mmdetection/blob/master/2.24.1_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmdetection:2.24.1_cpu``

* Tensorflow

  * `Tensorflow 1.14, Object Detection API 2019-08-31, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/object_detection/1.14.0_2019-08-31>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tf_object_detection:1.14.0_2019-08-31``

* Tensorflow (using our `wai.tflite_model_maker <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker>`__ Python library)

  * `2.4.3, CUDA 11.0 <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tflite_model_maker:2.4.3``

  * `2.4.3, CPU <https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tflite_model_maker:2.4.3_cpu``

* PyTorch/Yolov5

  * `Yolov5 2022-01-21, CPU <https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-01-21_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-yolov5:2022-01-21_cpu``

  * `Yolov5 2022-01-21, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-01-21_cuda11.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-yolov5:2022-01-21_cuda11.1``

  * `Yolov5 2022-05-31, CPU <https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-05-31_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-yolov5:2022-05-31_cpu``

  * `Yolov5 2022-05-31, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-05-31_cuda11.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-yolov5:2022-05-31_cuda11.1``

  * `Yolov5 2022-09-29, CPU <https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-09-29_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-yolov5:2022-09-29_cpu``

  * `Yolov5 2022-09-29, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-09-29_cuda11.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-yolov5:2022-09-29_cuda11.1``

* PyTorch/Yolov7

  * `Yolov7 2022-10-08, CPU <https://github.com/waikato-datamining/pytorch/tree/master/yolov7/2022-10-08_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-yolov7:2022-10-08_cpu``

  * `Yolov7 2022-10-08, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/yolov7/2022-10-08_cuda11.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/pytorch-yolov5:2022-10-08_cuda11.1``


Image segmentation
------------------

* Tensorflow/Keras

  * `image-segmentation-keras 0.3.0, Tensorflow 1.14, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/image-segmentation-keras/1.14.0_0.3.0>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/image-segmentation-keras:1.14.0_0.3.0``

  * `image-segmentation-keras 0.3.0, Tensorflow 2.4.1, CUDA 11.0 <https://github.com/waikato-datamining/tensorflow/tree/master/image-segmentation-keras/2.4.1_0.3.0>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/image-segmentation-keras:2.4.1_0.3.0``

* PyTorch

  * `Segmentation Models 0.2.1, PyTorch 1.9.0, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/segmentation_models/0.2.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/segmentation_models:0.2.1``

  * `MMSegmentation 0.25.0, PyTorch 1.9 and CUDA 11.1 <https://github.com/waikato-datamining/mmsegmentation/blob/master/0.25.0_cuda11.1>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmsegmentation:0.25.0_cuda11.1``

  * `MMSegmentation 0.25.0, PyTorch 1.9 and CPU <https://github.com/waikato-datamining/mmsegmentation/blob/master/0.25.0_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/open-mmlab/mmsegmentation:0.25.0_cpu``


Instance segmentation
---------------------

* PyTorch/Detectron2

  * `Detectron2 0.3, PyTorch 1.6, CUDA 10.1 <https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.3>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/detectron2:0.3``

  * `Detectron2 0.5, PyTorch 1.9, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.5>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/detectron2:0.5``

  * `Detectron2 0.6, PyTorch 1.9, CUDA 11.1 <https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.6>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/pytorch/detectron2:0.6``

* PyTorch/YOLACT++

  * `YOLACT++ 2020-02-11, PyTorch 1.2, CUDA 10.0 <https://github.com/waikato-datamining/yolact/tree/master/yolactpp-2020-02-11>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/yolact/yolactpp:2020-02-11``

* Tensorflow/Object Detection API

  * `Tensorflow 1.14, Object Detection API 2019-08-31, CUDA 10.0 <https://github.com/waikato-datamining/tensorflow/tree/master/object_detection/1.14.0_2019-08-31>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tf_object_detection:1.14.0_2019-08-31``



Speech-to-text (STT)
--------------------

* Coqui STT

  * `Coqui STT 1.3.0, CUDA 11.0 <https://github.com/waikato-datamining/tensorflow/blob/master/coqui/stt/1.3.0_cuda11.0>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tf_coqui_stt:1.3.0_cuda11.0``

  * `Coqui STT 1.3.0, CPU <https://github.com/waikato-datamining/tensorflow/blob/master/coqui/stt/1.3.0_cpu>`__

    ``public.aml-repo.cms.waikato.ac.nz:443/tensorflow/tf_coqui_stt:1.3.0_cpu``
