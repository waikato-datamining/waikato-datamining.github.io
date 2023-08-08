.. title: Redis-related Docker image updates
.. slug: 2023-08-09-redis_updates
.. date: 2023-08-09 11:41:00 UTC+12:00
.. tags: update
.. category: docker
.. link: 
.. description: 
.. type: text

The `redis-docker-harness <https://github.com/waikato-datamining/redis-docker-harness>`__
Python library, which is used by a lot of our Docker images, has received a number of updates
(at time of writing, the version of the library in use is 0.0.4):

* ability to specify a password for the Redis server
* specify the timeout parameter for the the Redis client, with larger timeouts resulting in
  lower CPU load (the default is now 0.01 instead of 0.001)

Unfortunately, this required re-releasing the most recent images of the following frameworks:

* detectron2
* mmdetection
* mmsegmentation
* yolov5
* yolov7
* Segment Anything (SAM)
* DEXTR

The images kept their version number, you just need to pull them again, or use `--pull ALWAYS`
in conjunction with `docker run`.
