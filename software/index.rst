.. title: Software
.. slug: software
.. date: 2024-11-26 12:01:00 UTC+13:00
.. tags: 
.. category: software
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
   - right-aligning image in header: https://thesoftwarearchitect.com/bootstrap-4-cardheader-with-buttons-on-the-right/
   - icons from: https://www.iconfinder.com/

.. raw:: html

    <nav aria-label="breadcrumb">
      <ol class="breadcrumb">
        <li class="breadcrumb-item"><a href="/resources">Resources</a></li>
        <li class="breadcrumb-item active" aria-current="page">Software</li>
      </ol>
    </nav>

    <p>A non-exhaustive list of our open-source software:</p>

    <div class="card-group">
      <div class="row row-cols-1 row-cols-sm-1 row-cols-md-2 row-cols-lg-3 row-cols-xl-3">

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">ADAMS</h3></div><img src="/images/adams_logo_no_text.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">A flexible workflow engine written in Java, for quickly building and maintaining data-driven, reactive workflows, easily integrated into business processes.</p>
              <a href="https://adams.cms.waikato.ac.nz/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">Docker Hub images</h3></div><img src="/images/8666171_docker_icon.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">Most of the software that we employ for our projects is open source. Therefore, the Docker images that we maintain for these projects (including extensions/enhancements) are publicly available and ready for you to use.</p>
              <a href="/docker-images-dockerhub/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">audio-dataset-converter</h3></div><img src="/images/171275_volume_high_sound_audio_speaker_icon.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">Training speech-to-text (STT) models requires data to be available in particular formats. Check out the examples for using our Python library for converting and processing audio dataset formats or even extracting speech from audio files.</p>
              <a href="/audio-dataset-converter-examples/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">image-dataset-converter</h3></div><img src="/images/211677_image_icon.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">Thinking about building image classification, object detection or image segmentation models? Then have a look the examples for using our Python library for converting and processing image dataset formats. You can even incorporate (pre-)trained models to generate annotations to further refine.</p>
              <a href="/image-dataset-converter-examples/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">llm-dataset-converter</h3></div><img src="/images/103408_text_book_icon.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">Working with diverse data sources (plain text, PDF, MS Word, Parquet DBs, etc.) can be challenging for compiling quality data for your large language model (LLM) training run. With our Python library for converting and processing LLM datasets, this will become much easier and you can do that straight from the command-line.</p>
              <a href="https://waikato-llm.github.io/llm-dataset-converter-examples/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">spectral-data-converter</h3></div><img src="/images/spectrum.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">Processing spectral data using command-line pipelines is easy and allows for convenient automation of processes. Conversion between formats is just one use-case, you can also clean and preprocess data, as well as build and apply scikit-learn models.</p>
              <a href="/spectral-data-converter-examples/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">Github</h3></div><img src="/images/211904_social_github_icon.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">Github organizations that encompass our code repositories, including libraries and Docker images:</p>
              <a href="https://github.com/waikato-datamining/" class="btn btn-primary mt-auto">waikato-datamining</a>
              <p/>
              <a href="https://github.com/waikato-llm/" class="btn btn-primary mt-auto">waikato-llm</a>
            </div>
          </div>
        </div>

      </div>
    </div>
