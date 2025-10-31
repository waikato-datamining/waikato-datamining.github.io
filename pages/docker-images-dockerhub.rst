.. title: Docker Hub images
.. slug: docker-images-dockerhub
.. date: 2025-05-29 19:50:00 UTC+12:00
.. tags: docker
.. category: software
.. link: 
.. description: 
.. type: text
.. hidetitle: True


.. raw:: html

    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <li class="breadcrumb-item"><a href="/resources">Resources</a></li>
        <li class="breadcrumb-item"><a href="/software">Software</a></li>
        <li class="breadcrumb-item active" aria-current="page">Docker Hub images</li>
      </ol>
    </nav>

    <p>The following images are available from <a href="https://hub.docker.com/u/waikatodatamining">Docker Hub</a>:</p>

    <p>Click on one of the domain buttons to see the relevant frameworks and images:</p>

    <!-- ------- -->
    <!-- buttons -->
    <!-- ------- -->

    <div data-toggle="buttons">
      <div class="mb-1">
        <button class="btn btn-primary btn-sm" type="button" data-toggle="collapse" data-target="#image-classification" aria-expanded="false" aria-controls="image-classification">
          Image classification
        </button>
        <button class="btn btn-primary btn-sm" type="button" data-toggle="collapse" data-target="#object-detection" aria-expanded="false" aria-controls="object-detection">
          Object detection
        </button>
        <button class="btn btn-primary btn-sm" type="button" data-toggle="collapse" data-target="#image-segmentation" aria-expanded="false" aria-controls="image-segmentation">
          Image segmentation
        </button>
        <button class="btn btn-primary btn-sm" type="button" data-toggle="collapse" data-target="#instance-segmentation" aria-expanded="false" aria-controls="instance-segmentation">
          Instance segmentation
        </button>
      </div>
      <div class="mb-1">
        <button class="btn btn-primary btn-sm" type="button" data-toggle="collapse" data-target="#large-language-models" aria-expanded="false" aria-controls="large-language-models">
          Large language models (LLM)
        </button>
        <button class="btn btn-primary btn-sm" type="button" data-toggle="collapse" data-target="#speech-to-text" aria-expanded="false" aria-controls="speech-to-text">
          Speech-to-text (STT)
        </button>
        <button class="btn btn-primary btn-sm" type="button" data-toggle="collapse" data-target="#text-classification" aria-expanded="false" aria-controls="text-classification">
          Text classification
        </button>
      </div>
    </div>

    <!-- -------------------- -->
    <!-- image classification -->
    <!-- -------------------- -->

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
            <p>PyTorch/MMPretrain (successor of MMClassification)</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmpretrain/blob/master/1.2.0_cuda11.1">MMPretrain 1.2.0, PyTorch 1.9 and CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmpretrain:1.2.0_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmpretrain/blob/master/1.2.0_cpu">MMPretrain 1.2.0, PyTorch 1.11 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmpretrain:1.2.0_cpu</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>PyTorch/PaddleClas</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/paddleclas/blob/master/2.6.0_cuda11.8">PaddleClas 2.6.0, PyTorch 2.5.1 and CUDA 11.8</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/paddleclas:2.6.0_cuda11.8</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/paddleclas/blob/master/2.6.0_cpu">PaddleClas 2.6.0, PyTorch 1.11.0 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/paddleclas:2.6.0_cpu</span></code></p>
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

    <!-- ---------------- -->
    <!-- object detection -->
    <!-- ---------------- -->

    <div class="collapse" id="object-detection">
      <div class="card card-body">
        <ul>
          <li>
            <p>PyTorch/MMDetection</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/blob/master/3.1.0_cuda11.3">MMDetection 3.1.0, PyTorch 1.12 and CUDA 11.3</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:3.1.0_cuda11.3</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmdetection/blob/master/3.1.0_cpu">MMDetection 3.1.0, PyTorch 1.12 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmdetection:3.1.0_cpu</span></code></p>
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
            <p>PyTorch/PaddleDetection</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/paddledetection/tree/main/2.8.0_cpu">PaddleDetection 2.8.0, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/paddledetection:2.8.0_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/paddledetection/tree/main/2.8.0_cuda11.8">PaddleDetection 2.8.0, CUDA 11.8</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/paddledetection:2.8.0_cuda11.8</span></code></p>
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
            <p>PyTorch/Yolov7</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov7/2022-10-08_cpu">Yolov7 2022-10-08, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov7:2022-10-08_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov7/2022-10-08_cuda11.1">Yolov7 2022-10-08, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov7:2022-10-08_cuda11.1</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>PyTorch/Yolov10</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov10/2024-06-23_cpu">Yolov10 2024-06-23, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov10:2024-06-23_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/yolov10/2024-06-23_cuda11.7">Yolov10 2024-06-23, CUDA 11.7</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-yolov10:2024-06-23_cuda11.1</span></code></p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>

    <!-- ------------------ -->
    <!-- image segmentation -->
    <!-- ------------------ -->

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
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmsegmentation/blob/master/1.2.2-3_cuda11.3">MMSegmentation 1.2.2, PyTorch 1.11.0 and CUDA 11.3</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmsegmentation:1.2.2-3_cuda11.3</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/mmsegmentation/blob/master/1.2.2-3_cpu">MMSegmentation 1.2.2, PyTorch 1.11.0 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/mmsegmentation:1.2.2-3_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/paddleseg/blob/master/2.10.0-3_cuda11.8">PaddleSeg 2.10.0, PyTorch 2.7.0 and CUDA 11.8</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/paddleseg:2.10.0-3_cuda11.8</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/paddleseg/blob/master/2.10.0-3_cpu">PaddleSeg 2.10.0, PyTorch 2.7.0 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/paddleseg:2.10.0-3_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/dextr/0.1.2_cuda11.1">DEXTR 0.1.2, PyTorch 1.10.0 and CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-dextr:0.1.2_cuda11.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/dextr/0.1.2_cpu">DEXTR 0.1.2, PyTorch 1.9.1 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-dextr:0.1.2_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/segment-anything/2023-04-16_cuda11.6">Segment-Anything Model 2023-04-16, PyTorch 1.13.0 and CUDA 11.6</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-sam:2023-04-16_cuda11.6</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/segment-anything/2023-04-16_cpu">Segment-Anything Model 2023-04-16, PyTorch 1.9.1 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-sam:2023-04-16_cpu</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/segment-anything-hq/2023-08-17_cuda11.6">Segment-Anything in High Quality 2023-08-17, PyTorch 1.13.0 and CUDA 11.6</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-sam-hq:2023-08-17_cuda11.6</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-datamining/pytorch/tree/master/segment-anything-hq/2023-08-17_cpu">Segment-Anything in High Quality 2023-08-17, PyTorch 1.9.1 and CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-sam-hq:2023-08-17_cpu</span></code></p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>

    <!-- --------------------- -->
    <!-- instance segmentation -->
    <!-- --------------------- -->

    <div class="collapse" id="instance-segmentation">
      <div class="card card-body">
        <ul>
          <li>
            <p>PyTorch/Detectron2</p>
            <ul>
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
        </ul>
      </div>
    </div>

    <!-- --------------------------- -->
    <!-- large language models (LLM) -->
    <!-- --------------------------- -->

    <div class="collapse" id="large-language-models">
      <div class="card card-body">
        <ul>
          <li>
            <p>BitNet</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-llm/bitnet/tree/main/2025-04-30_cpu">BitNet 2025-04-30, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/bitnet:2025-05-30_cpu</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>Falcontune</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-llm/huggingface_transformers/tree/main/4.31.0_cuda11.7_falcontune_20230618">Falcontune 20230618, CUDA 11.7</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-huggingface-transformers:4.31.0_cuda11.7_falcontune_20230618</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>finetune-gpt2xl</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-llm/huggingface_transformers/tree/main/4.7.0_cuda11.1_finetune-gpt2xl_20220924">finetune-gpt2xl 20220924, CUDA 11.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-huggingface-transformers:4.7.0_cuda11.1_finetune-gpt2xl_20220924</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>Llama-2</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-llm/huggingface_transformers/tree/main/4.31.0_cuda11.7_llama2">Llama2, CUDA 11.7</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-huggingface-transformers:4.31.0_cuda11.7_llama2</span></code></p>
              </li>
            </ul>
          </li>
          <li>
            <p>XTuner</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-llm/xtuner/tree/main/2024-02-19_cuda11.7">XTuner 2024-02-19, CUDA 11.7</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-xtuner:2024-02-19_cuda11.7</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-llm/xtuner/tree/main/0.1.15_cuda11.7">XTuner 0.1.15, CUDA 11.7</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-xtuner:0.1.15_cuda11.7</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-llm/xtuner/tree/main/0.1.18_cuda11.7">XTuner 0.1.18, CUDA 11.7</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-xtuner:0.1.18_cuda11.7</span></code></p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>

    <!-- -------------------- -->
    <!-- speech-to-text (STT) -->
    <!-- -------------------- -->

    <div class="collapse" id="speech-to-text">
      <div class="card card-body">
        <ul>
          <li>
            <p>OpenAI Whisper</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-llm/whisper/tree/main/faster-whisper-1.0.2_cuda12.1">Faster Whisper 1.0.2, CUDA 12.1</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/python-faster-whisper:1.0.2_cuda12.1</span></code></p>
              </li>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-llm/whisper/tree/main/faster-whisper-1.0.2_cpu">Faster Whisper 1.0.2, CPU</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/python-faster-whisper:1.0.2_cpu</span></code></p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>

    <!-- ------------------- -->
    <!-- text classification -->
    <!-- ------------------- -->

    <div class="collapse" id="text-classification">
      <div class="card card-body">
        <ul>
          <li>
            <p>Huggingface</p>
            <ul>
              <li>
                <p><a class="reference external" href="https://github.com/waikato-llm/huggingface_transformers/tree/main/4.36.0_cuda11.7_classification">Huggingface 4.36.0, CUDA 11.7</a></p>
                <p><code class="docutils literal"><span class="pre">waikatodatamining/pytorch-huggingface-transformers:4.36.0_cuda11.7_classification</span></code></p>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>

   <p/>


For some of the frameworks, we have tutorials available on how to use them in practice. This includes data preparation, training and making predictions. Check out our `Applied Deep Learning </applied-deep-learning/>`__ site for more details.
