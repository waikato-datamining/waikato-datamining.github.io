.. title: S3000 Python support
.. slug: 2025-03-04-s3000-python-support
.. date: 2025-03-04 17:07:00 UTC+13:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text

Our commercial offering for laboratories, `S3000 <link://slug/s3000>`__, now has official
support for custom Python models. Being a Java application, S3000 historically relied on Weka for its modeling.
However, with the integration of `Jep <https://github.com/ninia/jep>`__ (Java Embedded Python) in ADAMS, it is now
possible to use scikit-learn or deep learning libraries for training models and making predictions.

In order to make this work, ADAMS needs to launch from the context of an activated virtual Python environment
that contains all the required Python libraries and then use the `JepRegressor` Weka meta-classifier to define
the relevant code for training and making predictions. Due to Java serialization not being applicable to Python objects,
these scripts must implement the relevant serialization/deserialization themselves, e.g., via pickle.
