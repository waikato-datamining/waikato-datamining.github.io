.. title: simple-confusion-matrix library released
.. slug: 2021-04-16-simple-confusion-matrix
.. date: 2021-04-16 14:29:00 UTC+12:00
.. tags: release
.. category: library
.. link: 
.. description: 
.. type: text

The **simple-confusion-matrix** Python 3 library has been released today:

`github.com/waikato-datamining/simple-confusion-matrix <https://github.com/waikato-datamining/simple-confusion-matrix>`__

It is a simple library that can generate confusion matrices from CSV
files or lists of actual and predicted labels. It can output the generated
matrix either in plain text or CSV, as string or to a file.

Rather than just using counts, it can generate also:

* percentages (all cells sum up to 1)
* percentages per row (all cells in a row sum up to 1)

The latter is useful when dealing with imbalanced datasets, giving you a good idea of
how well each label is being predicted.

