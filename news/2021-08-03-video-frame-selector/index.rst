.. title: video-frame-selector library released
.. slug: 2021-08-03-video-frame-selector
.. date: 2021-08-03 11:20:00 UTC+12:00
.. tags: release
.. category: library
.. link: 
.. description: 
.. type: text

The **video-frame-selector** Python 3 library is now available:

`github.com/waikato-datamining/video-frame-selector <https://github.com/waikato-datamining/video-frame-selector>`__

With this library you can present frames obtained from video files or a webcam to an image analysis framework,
such as `detectron2 <https://github.com/waikato-datamining/pytorch/tree/master/detectron2>`__, and react to the
generated predictions. For instance, you might want to trawl through a video from a trail camera and generate 
either JPG images or a shortened video that contains **only** the frames that show actual animal. Or you might
only look for a specific animal, rather than all of them (e.g., only NZ pests such as rats or stoats).
Frames that are to be kept can also be cropped to the smallest area that encompasses all the detected bounding 
boxes (you can enforce a margin around the cropped content and/or a minimum width/height).

