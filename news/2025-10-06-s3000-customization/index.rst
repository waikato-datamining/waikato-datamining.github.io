.. title: S3000 Customization
.. slug: 2025-10-06-s3000-customization
.. date: 2025-10-06 15:43:00 UTC+12:00
.. tags: update
.. category: software
.. link:
.. description:
.. type: text


Out of the box, our `S3000 <link://slug/s3000>`__ software comes with predefined workflow generator
plugins that can be configured to suit a customer's needs. However, sometimes it is necessary to further
refine that configuration, e.g., when generating statistics during training runs.
In order not to overload the generator plugins with even more options, or create customized generators,
the notion of *config tags* has been introduced. Generators that support such customization will
state so in their help screen and list the supported *tags*. These tags can then be customized in
the *ConfigTags.props* properties file.
