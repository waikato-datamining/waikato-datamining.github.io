.. title: Docker images
.. slug: docker-images
.. date: 2022-08-04 12:10:00 UTC+12:00
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
        <li class="breadcrumb-item active" aria-current="page">Docker images</li>
      </ol>
    </nav>

    <p>For our own projects, we make a lot of use of <a href="https://www.docker.com/">Docker</a>, to better manage
    the challenging requirements for CUDA and Python libraries. You can obtain the images from two sources:</p>

    <div class="card-group">
      <div class="row row-cols-1 row-cols-sm-2 row-cols-md-2 row-cols-lg-2 row-cols-xl-2">

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">In-house Registry</h3></div><img src="/images/adams_logo_no_text.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">The Docker images are hosted on campus on our own infrastructure, with any base images cached here as well. From within New Zealand, this could result in faster downloads.</p>
              <a href="/docker-images-inhouse/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">Docker Hub</h3></div><img src="/images/adams_logo_no_text.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">Using Docker's <a href="https://hub.docker.com/">hosting facility</a>, this approach will give you access to our Docker images anywhere in the world.</p>
              <a href="/docker-images-dockerhub/" class="btn btn-primary stretched-link mt-auto">More...</a>
            </div>
          </div>
        </div>

      </div>
    </div>


For some of the frameworks, we have tutorials available on how to use them in practice. This includes data preparation, training and making predictions. Check out our `Applied Deep Learning </applied-deep-learning/>`__ site for more details.
