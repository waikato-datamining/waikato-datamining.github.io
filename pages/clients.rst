.. title: Our Clients
.. slug: clients
.. date: 2024-09-02 14:07:00 UTC+12:00
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


    <div class="display-5"><h3>Our Clients</h3></div>
    <p>Below are some of our clients that we are working with:</p>

    <div class="card-group">
      <div class="row row-cols-1 row-cols-sm-1 row-cols-md-2 row-cols-lg-3 row-cols-xl-3">

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-body d-flex flex-column">
              <a href="https://www.agresearch.co.nz/" target="_blank"><img src="../images/client_agresearch.png" class="card-img-top" alt="AgResearch Logo"></a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-body d-flex flex-column">
              <a href="https://www.ravensdown.co.nz/services/testing" target="_blank"><img src="../images/client_arl.png" class="card-img-top" alt="ARL Logo"></a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-body d-flex flex-column">
              <a href="http://www.c3.co.nz/" target="_blank"><img src="../images/client_c3.jpg" class="card-img-top" alt="C3 Logo"></a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-body d-flex flex-column">
              <a href="https://www.eurofins.com/agro" target="_blank"><img src="../images/client_eurofins_agro.jpg" class="card-img-top" alt="Eurofins Agro Logo"></a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-body d-flex flex-column">
              <a href="https://www.plantandfood.co.nz/" target="_blank"><img src="../images/client_pfr.png" class="card-img-top" alt="Plant and Food Research Logo"></a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-body d-flex flex-column">
              <a href="http://www.redfernsolutions.co.nz/" target="_blank"><img src="../images/client_redfern.png" class="card-img-top" alt="Redfern Solutions Logo"></a>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-body d-flex flex-column">
              <a href="http://www.zespri.com/" target="_blank"><img src="../images/client_zespri.jpg" class="card-img-top" alt="Zespri Logo"></a>
            </div>
          </div>
        </div>

      </div>
    </div>
