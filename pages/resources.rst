.. title: Resources
.. slug: resources
.. date: 2024-11-25 12:01:00 UTC+13:00
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

    <div class="card-group">
      <div class="row row-cols-1 row-cols-sm-1 row-cols-md-2 row-cols-lg-2 row-cols-xl-2">

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">Software</h3></div><img src="/images/4960322_app_cogwheel_computer_pc_software_icon.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">Over the years, we have developed and incorporated a lot of libraries and applications. Here is an overview of some of the current software that develop and/or utilize for projects.</p>
              <a href="/software/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">Docker for Data Scientists</h3></div><img src="/images/11807231_video_lectures_education_learning_tutorial_icon.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">If you are a data Data Scientist and unsure how you can use/utilize Docker for your work or even in your organization, then have a look at our tutorial. It will you show the basics of using existing Docker images as well as how you can write your own ones.</p>
              <a href="/docker-for-data-scientists/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">Applied Deep Learning</h3></div><img src="/images/11807231_video_lectures_education_learning_tutorial_icon.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">With our ready-to-use Docker images, you can dive into building models. Our tutorial on applied deep learning shows you how to utilize our Docker images for data domains like image classification, object detection and image segmentation.</p>
              <a href="/applied-deep-learning/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">Spectral datasets</h3></div><img src="/images/352553_audio_multitrack_icon.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">Looking for publicly available <a href="https://en.wikipedia.org/wiki/Near-infrared_spectroscopy">NIRS</a> datasets that are in an easy to read format and do not require much work before you can train/optimize your models? Then head over to our Github repository of public spectral datasets and get started!</p>
              <a href="https://spectral-datasets.github.io/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

      </div>
    </div>
