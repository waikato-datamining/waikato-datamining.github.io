.. title: Expertise
.. slug: expertise
.. date: 2024-11-20 10:34:00 UTC+13:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
.. hidetitle: True


..
   Notes on bootstrap:
   - "card h-100" - makes the cards to 100% height of parent
   - "row-cols-sm-1" - on small screen use one column (-md-/medium, -lg-/large, -xl-/extra-large)
   - "mb-4" - sets margin/bottom to 4
   - "card-body d-flex flex-column" - ensures that all columns are same height
   - "stretched-link" in link - makes whole card clickable
   - "mt-auto" - set margin top to automatic
   - source: https://stackoverflow.com/a/48406823/4698227

.. raw:: html

    <div class="card-group">
      <div class="row row-cols-1 row-cols-sm-1 row-cols-md-1 row-cols-lg-1 row-cols-xl-1">

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header"><h3 class="display-5">Spectral data analysis</h3></div>
            <div class="card-body">
              <div class="row">
                <div class="col-lg-10">
                    <div>
                      <p class="card-text">For more than fifteen years, we have developed and deployed software that takes advantage of machine learning models to predict properties of plant and soil samples, using spectra from various instruments: near-infrared (<a href="https://en.wikipedia.org/wiki/Near-infrared_spectroscopy">NIR</a>), mid-infrared (MIR), laser-incuded breakdown spectroscopy (<a href="https://en.wikipedia.org/wiki/Laser-induced_breakdown_spectroscopy">LIBS</a>) and X-ray fluorescence (<a href="https://en.wikipedia.org/wiki/X-ray_fluorescence">XRF</a>).</p>
                      <p class="card-text">For decades, many organizations have relied on global methods like partial least squares regression (<a href="https://en.wikipedia.org/wiki/Partial_least_squares_regression">PLS</a>) for their modeling. However, global methods do not perform well with complex data derived from, for instance, soil samples. From the start, our software took advantage of locally weighted learning, achieving much better results.</p>
                      <p class="card-text">In recent years, we have been able to push the boundaries even further, by adopting advanced modeling techniques using <a href="https://en.wikipedia.org/wiki/Deep_learning">deep learning</a>.</p>
                      <p class="card-text">Our commercial <a href="/s3000/">S3000 software</a> can not only be used for building models on your data, but also for integrating into your business processes.</p>
                    </div>
                </div>
                <div class="col-lg-2 hover-shadow">
                  <a class="reference external image-reference" href="../images/methods.png"><figure><img alt="Comparison of spectral data analysis methods" class="align-right" src="../images/methods.png"></figure></a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header"><h3 class="display-5">Hyperspectral imaging</h3></div>
            <div class="card-body">
              <div class="row">
                <div class="col-lg-10">
                    <div>
                      <p class="card-text">The last few years, we have been expanding our expertise to hyperspectral imaging (<a href="https://en.wikipedia.org/wiki/Hyperspectral_imaging">HSI</a>) as well. After the <a href="https://www.waikato.ac.nz/about/faculties-schools/engineering/">School of Engineering</a> purchased a <a href="https://hsi.eng.waikato.ac.nz/hardware/">hyperspectral camera</a>, we developed a Python-based suite of tools called <a href="https://hsi.eng.waikato.ac.nz/happy/">HAPPy</a> (Hyperspectral Application Platform in Python) for annotating and processing their data.</p>
                      <p class="card-text">On the one hand, the suite contains graphical tools that allow viewing of the captured data, as well as annotating the images (either using polygons or on a pixel-level). On the other hand, you have the ability to define and run command-line pipelines over your data to allow for repeatable data conversions and model building (using <a href="https://scikit-learn.org/">scikit-learn</a> or <a href="https://keras.io/">Keras</a>).</p>
                    </div>
                </div>
                <div class="col-lg-2 hover-shadow">
                  <a class="reference external image-reference" href="../images/happy_viewer.png"><figure><img alt="Viewer interface of the HAPPy tools" class="align-right" src="../images/happy_viewer.png"></figure></a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header"><h3 class="display-5">Image processing</h3></div>
            <div class="card-body">
              <div class="row">
                <div class="col-lg-10">
                    <div>
                      <p class="card-text">With the advent of frameworks like <a href="https://en.wikipedia.org/wiki/TensorFlow">Tensorflow</a> and <a href="https://en.wikipedia.org/wiki/PyTorch">PyTorch</a>, deep learning techniques became more accessible. Many cutting edge algorithms and libraries have complex dependencies that not only interfer with each other, but also change frequently. These libraries are often geared towards academic experimentation and not production-ready. By employing containerization offered by <a href="https://en.wikipedia.org/wiki/Docker_(software)">Docker</a> and custom extensions, we are able to deploy these frameworks in production environments (for training and inference).</p>
                      <p class="card-text">We have extensive experience in the following areas:</p>
                      <p class="card-text">image classification, object detection, instance segmentation, image segmentation</p>
                    </div>
                </div>
                <div class="col-lg-2 hover-shadow">
                  <a class="reference external image-reference" href="../images/objdet.png"><figure><img alt="Object detection of cars" class="align-right" src="../images/objdet.png"></figure></a>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header"><h3 class="display-5">Natural language processing</h3></div>
            <div class="card-body">
              <div class="row">
                <div class="col-lg-10">
                    <div>
                      <p class="card-text"><a href="https://openai.com/">OpenAI</a> pushed the envelop with their <a href="https://chatgpt.com/">ChatGPT</a> models and how models can chat naturally with humans. Only very few organizations are in a position nowadays to build such large language models (LLMs), as they require not only huge amounts of data but also massive hardware (<a href="https://ai.meta.com/blog/meta-llama-3-1/">Meta's Llama 3.1 was trained on 16,000 H100 GPUs</a>). However, a lot of these models can be used locally and, if necessary, further fine-tuned. Smaller variants of the models, which are still very capable, can even be run on consumer-grade hardware. That way, you can make sure that your data stays local and confidential (<a href="https://en.wikipedia.org/wiki/Data_sovereignty">data sovereignty</a>).</p>
                      <p class="card-text">We can work with you in the following domains:</p>
                      <p class="card-text">automatic speech recognition, small and large language models (SLMs/LLMs)</p>
                    </div>
                </div>
                <div class="col-lg-2 hover-shadow">
                  <a class="reference external image-reference" href="../images/asr.png"><figure><img alt="Automatic speech recognition" class="align-right" src="../images/asr.png"></figure></a>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
