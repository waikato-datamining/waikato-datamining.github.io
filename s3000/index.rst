.. title: S3000
.. slug: s3000
.. date: 2021-08-09 11:00:00 UTC+12:00
.. tags: 
.. category: software
.. link: 
.. description: 
.. type: text


Our commercial S3000 software is aimed at environmental laboratories that analyze soil and plant samples using
spectroscopy (`NIR <https://en.wikipedia.org/wiki/Near-infrared_spectroscopy>`__, MIR,
`LIBS <https://en.wikipedia.org/wiki/Laser-induced_breakdown_spectroscopy>`__ or
`XRF <https://en.wikipedia.org/wiki/X-ray_fluorescence>`__).

Instead of using calibrations that the NIR manufacturers sell with their instruments, our system offers a bigger
range of pre-processing techniques and sophisticated algorithms (due to our background in machine learning).

S3000 is based on our `ADAMS <https://adams.cms.waikato.ac.nz/>`__ workflow software and offers the following
benefits:

* cross-platform (Linux, Windows, Mac)
* easy to extend plugin-architecture for client-specific customizations
* easy integration into existing business processes
* can make use of co-variables determined in the lab to improve models
* automated/scheduled training possible
* can generate PDF report for models, incl. parameter settings and performance (useful for accreditation)
* can flag unreliable predictions
* supports common spectral file formats (CAL, JCamp-DX, NIR, Opus, SPA, SPC, spreadsheet-based, Unscrambler)
* supports data retrieval from databases via `JDBC <https://en.wikipedia.org/wiki/Java_Database_Connectivity>`__
* offers provenance, i.e., tracing samples as they go through the system
* (optional) web-interface for basic administrative and monitoring tasks
* unlimited number of models
* unlimited number of import tasks
* ability to add custom tasks via external ADAMS workflows
* scripting support via `Groovy <https://groovy-lang.org/>`__
