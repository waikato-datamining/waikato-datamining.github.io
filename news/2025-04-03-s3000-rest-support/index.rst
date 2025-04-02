.. title: S3000 REST webservice support
.. slug: 2025-04-03-s3000-rest-support
.. date: 2025-04-03 10:35:00 UTC+13:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text

While our commercial framework for laboratories, `S3000 <link://slug/s3000>`__, had support for
making predictions via `webservices <https://en.wikipedia.org/wiki/Web_service>`__ for a long time,
that was limited to asynchronous ones: a webservice endpoint receives data coming in and, once the
predictions have been generated, the results get forwarded to another webservice.

With recent changes to the codebase, it is now possible to offer synchronous `REST webservices <https://en.wikipedia.org/wiki/REST>`__
as well. In order to reduce latency as much as possible, provenance logging under the hood
has been modified to have a much higher throughput that no longer impacts the speed of the predictions.

Thanks to the plugin architecture of S3000, customer-specific webservices can be implemented and deployed
with minimal effort.
