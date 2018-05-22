==================
Dependencies
==================

You'll need a Python module called PIL (the Python Imaging Library),
which is used to generate the output images in this problem set.
There are a number of easy ways to get PIL.

PIL is available as a package named python-imaging. You can install it by typing

$ sudo apt-get install python-imaging


==================
Running the tests
==================

PLEASE NOTE: Before running the tests, please be sure to read and follow the instructions listed in the programming assignment on Haiku.

A few simple sanity tests are provided; you can run them by typing

$ python test_dnaseq.py

To run the full comparison program, run

$ python dnaseq.py data/inputa0.fa data/inputb0.fa output.png

(You should change the first two arguments to match the inputs you're
interested in.)
