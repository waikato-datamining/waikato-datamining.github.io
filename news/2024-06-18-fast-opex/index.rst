.. title: fast-opex released
.. slug: 2024-06-18-fast-opex
.. date: 2024-06-18 16:51:00 UTC+12:00
.. tags: release
.. category: software
.. link: 
.. description: 
.. type: text


The OPEX (`Object Predictions EXchange <https://github.com/WaikatoLink2020/objdet-predictions-exchange-format>`__)
format features heavily in our docker images for storing/broadcasting predictions. However, last week I noticed
that it incurs quite a significant speed penalty due to its use of JSON schema under the hood.
Since we want to be as fast as possible at prediction time, I sat down and rewrote the library using very basic
(but fast) checks and released it under the name **fast-opex**. The new library works as a drop-in replacement, i.e.,
you only have to switch from installing **opex** to **fast-opex**.

To further speed things up, the new library can take advantage of the blazingly fast
`orjson <https://github.com/ijl/orjson>`__ JSON library. The orjson library only needs to be present in the
environment and it will be used automatically.

If you are interested in a speed comparison, then head over to the following repository:

`https://github.com/waikato-datamining/opex-comparison <https://github.com/waikato-datamining/opex-comparison>`__
