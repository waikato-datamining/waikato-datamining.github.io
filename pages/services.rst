.. title: Services
.. slug: services
.. date: 2024-11-20 10:33:00 UTC+13:00
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
      <div class="row row-cols-1 row-cols-sm-1 row-cols-md-2 row-cols-lg-2 row-cols-xl-3">

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">Consulting</h3></div><img src="/images/11019390_accountant_banker_financial_advisor_people_icon.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">We can perform investigative data analysis studies of your data, to gauge the potential for commercial application.</p>
              <p class="card-text">With our advanced modeling techniques, we can support your scientists/domain experts get more out of your data and give your publications a boost.</p>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">Commercial applications</h3></div><img src="/images/1737376_dollar_money_sign_icon.png" height="24"/></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">A model is useless unless it can be integrated into business processes, which we have been doing for a long time.</p>
              <p class="card-text">Using this knowledge, we can also turn research ideas into commercial applications with funding through <a href="http://www.callaghaninnovation.govt.nz/">Callaghan Innovation</a>.</p>
            </div>
          </div>
        </div>

        <div class="col mb-4">
          <div class="card h-100 shadow">
            <div class="card-header d-flex justify-content-between align-items-center"><div><h3 class="display-5">Research opportunities</div><img src="/images/6382027_chemical_experiment_lab_laboratory_microscope_icon.png" height="24"/></h3></div>
            <div class="card-body d-flex flex-column">
              <p class="card-text">We are happy to act as sub-contractor for data modeling or data analysis on your <a href="http://www.mbie.govt.nz/">MBIE</a> bid, strengthening your chances of success with our excellent track record in that space.</p>
            </div>
          </div>
        </div>

      </div>
    </div>
