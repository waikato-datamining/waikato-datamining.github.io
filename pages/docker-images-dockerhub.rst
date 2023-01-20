.. title: Docker Hub images
.. slug: docker-images-dockerhub
.. date: 2023-01-17 08:55:00 UTC+13:00
.. tags: docker
.. category: software
.. link: 
.. description: 
.. type: text


The following images are available from `Docker Hub <https://hub.docker.com/u/waikatodatamining>`__
(`tutorial <https://www.data-mining.co.nz/applied-deep-learning/>`__):

For some of the frameworks, we have tutorials available on how to use them in practice. This includes data
preparation, training and making predictions.

`https://www.data-mining.co.nz/applied-deep-learning/ <https://www.data-mining.co.nz/applied-deep-learning/>`__


.. raw:: html

    <p>Click on one of the domain buttons to see the relevant frameworks and images:</p>
    <p>
      <button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#image-classification" aria-expanded="false" aria-controls="image-classification">
        Image classification
      </button>
    </p>
    <div class="collapse" id="image-classification">
      <div class="card card-body">
        <ul>
          <li>
            <p>PyTorch (using our <a class="reference external" href="https://pypi.org/project/wai.pytorchimageclass/">wai.pytorchimageclass</a> Python library)</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/image-classification/docker/1.6.0">PyTorch 1.6.0, CUDA 10.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-image-classification:1.6</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/image-classification/docker/1.6.0_cpu">PyTorch 1.6.0, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-image-classification:1.6_cpu</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>PyTorch/MMClassification</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmclassification/blob/master/0.23.1_cuda11.1">MMClassification 0.23.1, PyTorch 1.9 and CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmclassification:0.23.1_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmclassification/blob/master/0.23.1_cpu">MMClassification 0.23.1, PyTorch 1.9 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmclassification:0.23.1_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmclassification/blob/master/0.25.0_cuda11.1">MMClassification 0.25.0, PyTorch 1.9 and CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmclassification:0.25.0_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmclassification/blob/master/0.25.0_cpu">MMClassification 0.25.0, PyTorch 1.9 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmclassification:0.25.0_cpu</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>Tensorflow (using our <a class="reference external" href="https://pypi.org/project/wai.tfimageclass/">wai.tfimageclass</a> Python library)</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/image_classification/docker/1.14">Tensorflow 1.14, CUDA 10.0</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tf_image_classification:1.14</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/image_classification/docker/1.14_cpu">Tensorflow 1.14, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tf_image_classification:1.14_cpu</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>Tensorflow (using our <a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker">wai.tflite_model_maker</a> Python library)</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3">2.4.3, CUDA 11.0</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tflite_model_maker:2.4.3</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3_cpu">2.4.3, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tflite_model_maker:2.4.3_cpu</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>Tensorflow (using the <a class="reference external" href="https://github.com/tensorflow/hub/tree/master/tensorflow_hub/tools/make_image_classifier">make_image_classifier</a> Python library)</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/image_classification2/2.9.1_cuda11.1">2.9.1, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tf_image_classification2:2.9.1_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/image_classification2/2.9.1_cpu">2.9.1, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tf_image_classification2:2.9.1_cpu</span></code></p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>

    <p>
      <button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#object-detection" aria-expanded="false" aria-controls="object-detection">
        Object detection
      </button>
    </p>
    <div class="collapse" id="object-detection">
      <div class="card card-body">
        <ul>
          <li>
            <p>PyTorch/MMDetection</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/tree/master/2020-03-01">MMDetection 2020-03-01, PyTorch 1.3 and CUDA 10.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:2020-03-01</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/blob/master/2.16.0">MMDetection 2.16.0, PyTorch 1.6 and CUDA 10.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:2.16.0</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/blob/master/2.16.0_cuda11.1">MMDetection 2.16.0, PyTorch 1.9 and CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:2.16.0_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/blob/master/2.16.0_cpu">MMDetection 2.16.0, PyTorch 1.9 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:2.16.0_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/blob/master/2.18.1_cuda11.1">MMDetection 2.18.1, PyTorch 1.9 and CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:2.18.1_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/blob/master/2.18.1_cpu">MMDetection 2.18.1, PyTorch 1.9 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:2.18.1_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/blob/master/2.24.1_cuda11.1">MMDetection 2.24.1, PyTorch 1.9 and CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:2.24.1_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/blob/master/2.24.1_cpu">MMDetection 2.24.1, PyTorch 1.9 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:2.24.1_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/blob/master/2.27.0_cuda11.1">MMDetection 2.27.0, PyTorch 1.9 and CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:2.27.0_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/blob/master/2.27.0_cpu">MMDetection 2.27.0, PyTorch 1.9 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:2.27.0_cpu</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>Tensorflow</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/object_detection/1.14.0_2019-08-31">Tensorflow 1.14, Object Detection API 2019-08-31, CUDA 10.0</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tf_object_detection:1.14.0_2019-08-31</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>Tensorflow (using our <a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker">wai.tflite_model_maker</a> Python library)</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3">2.4.3, CUDA 11.0</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tflite_model_maker:2.4.3</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/tflite_model_maker/docker/2.4.3_cpu">2.4.3, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tflite_model_maker:2.4.3_cpu</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>PyTorch/Yolov5</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-01-21_cpu">Yolov5 2022-01-21, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov5:2022-01-21_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-01-21_cuda11.1">Yolov5 2022-01-21, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov5:2022-01-21_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-05-31_cpu">Yolov5 2022-05-31, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov5:2022-05-31_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-05-31_cuda11.1">Yolov5 2022-05-31, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov5:2022-05-31_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-09-29_cpu">Yolov5 2022-09-29, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov5:2022-09-29_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-09-29_cuda11.1">Yolov5 2022-09-29, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov5:2022-09-29_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-11-05_cpu">Yolov5 2022-11-05, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov5:2022-11-05_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-11-05_cuda11.1">Yolov5 2022-11-05, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov5:2022-11-05_cuda11.1</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>PyTorch/Yolov7</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov7/2022-10-08_cpu">Yolov7 2022-10-08, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov7:2022-10-08_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov7/2022-10-08_cuda11.1">Yolov7 2022-10-08, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov5:2022-10-08_cuda11.1</span></code></p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>

    <p>
      <button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#image-segmentation" aria-expanded="false" aria-controls="image-segmentation">
        Image segmentation
      </button>
    </p>
    <div class="collapse" id="image-segmentation">
      <div class="card card-body">
        <ul>
          <li>
            <p>Tensorflow/Keras</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/image-segmentation-keras/1.14.0_0.3.0">image-segmentation-keras 0.3.0, Tensorflow 1.14, CUDA 10.0</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/image-segmentation-keras:1.14.0_0.3.0</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/image-segmentation-keras/2.4.1_0.3.0">image-segmentation-keras 0.3.0, Tensorflow 2.4.1, CUDA 11.0</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/image-segmentation-keras:2.4.1_0.3.0</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>PyTorch</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/segmentation_models/0.2.1">Segmentation Models 0.2.1, PyTorch 1.9.0, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/segmentation_models:0.2.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmsegmentation/blob/master/0.25.0_cuda11.1">MMSegmentation 0.25.0, PyTorch 1.9 and CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmsegmentation:0.25.0_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmsegmentation/blob/master/0.25.0_cpu">MMSegmentation 0.25.0, PyTorch 1.9 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmsegmentation:0.25.0_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmsegmentation/blob/master/0.30.0_cuda11.1">MMSegmentation 0.30.0, PyTorch 1.9 and CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmsegmentation:0.30.0_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmsegmentation/blob/master/0.30.0_cpu">MMSegmentation 0.30.0, PyTorch 1.9 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmsegmentation:0.30.0_cpu</span></code></p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>

    <p>
      <button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#instance-segmentation" aria-expanded="false" aria-controls="instance-segmentation">
        Instance segmentation
      </button>
    </p>
    <div class="collapse" id="instance-segmentation">
      <div class="card card-body">
        <ul>
          <li>
            <p>PyTorch/Detectron2</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.3">Detectron2 0.3, PyTorch 1.6, CUDA 10.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/detectron2:0.3</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.5">Detectron2 0.5, PyTorch 1.9, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/detectron2:0.5</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/detectron2/0.6">Detectron2 0.6, PyTorch 1.9, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/detectron2:0.6</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>PyTorch/YOLACT++</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/yolact/tree/master/yolactpp-2020-02-11">YOLACT++ 2020-02-11, PyTorch 1.2, CUDA 10.0</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/yolactpp:2020-02-11</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>PyTorch/Yolov5</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-11-05_cpu">Yolov5 2022-11-05, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov5:2022-11-05_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov5/2022-11-05_cuda11.1">Yolov5 2022-11-05, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov5:2022-11-05_cuda11.1</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>Tensorflow/Object Detection API</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/tree/master/object_detection/1.14.0_2019-08-31">Tensorflow 1.14, Object Detection API 2019-08-31, CUDA 10.0</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tf_object_detection:1.14.0_2019-08-31</span></code></p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>

    <p>
      <button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#speech-to-text" aria-expanded="false" aria-controls="speech-to-text">
        Speech-to-text (STT)
      </button>
    </p>
    <div class="collapse" id="speech-to-text">
      <div class="card card-body">
        <ul>
          <li>
            <p>Coqui STT</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/blob/master/coqui/stt/1.3.0_cuda11.0">Coqui STT 1.3.0, CUDA 11.0</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tf_coqui_stt:1.3.0_cuda11.0</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/tensorflow/blob/master/coqui/stt/1.3.0_cpu">Coqui STT 1.3.0, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/tf_coqui_stt:1.3.0_cpu</span></code></p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
