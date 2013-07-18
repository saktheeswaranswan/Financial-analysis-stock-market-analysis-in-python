Financial Analysis in Python
============================

Tutorial at PyData Boston 2013 July 27, 2013 at 4:30 pm.
http://pydata.org/bos2013/schedule/

*Thomas Wiecki, Quantopian Inc. and Brown University*

Thomas Wiecki is a Quantitative Researcher at Quantopian Inc -- a
Boston based startup providing you with the first browser based
algorithmic trading platform -- and a PhD student at Brown University
where he studies Computational Cognitive Neuroscience. He specializes
Bayesian Inference, Machine Learning, Scientific Computing in Python,
algorithmic trading and Computational Psychiatry.

Description
-----------

This tutorial will provide hands-on experience of various data
analysis tools relevant for financial analysis in Python. We will
first see how financial data can be imported from various sources such
as Yahoo! finance. Pandas, Matplotlib and statsmodels can be used for
basic and more advanced time-series analysis. While rudimentary
backtesting of investment strategies on historical data can be carried
out using Pandas, a more realistic simulation that considers
transaction costs, slippage and avoids look-ahead bias, introduces
various complexities. We will then see how Zipline, an open-source
streaming-based financial simulator written in Python, can make
realistic backtesting much easier. After going through some simple
example algorithms we will see how statistical Python libraries like
scikits.learn can easily be incorporated with Zipline to build
state-of-the art trading algorithms. Finally, I will briefly show how
the same algorithm code can be run with minimal code changes on
Quantopian -- a free, browser-based platform for developing
algorithmic trading models.

The target audience for the tutorial includes all new Python users,
though we recommend that users also attend the NumPy and IPython
session in the introductory track.

Student Instructions
--------------------

For students familiar with Git, you may simply clone this repository
to obtain all the materials (IPython notebooks and data) for the
tutorial. Alternatively, you may [](download a zip file) containing
the materials. A third option is to simply view static notebooks by
clicking on the titles of each section below.

Outline
-------

Required Packages
-----------------

* Python 2.7 (Python 3 is not supported at this point)
* pandas >= 0.11.1
* NumPy >= 1.6.1
* Matplotlib >= 1.0.0
* Zipline > TODO

For students running the latest version of Mac OS X (10.8), the
easiest way to obtain all the packages is to install the Scipy
Superpack which works with Python 2.7.2 that ships with OS X.

Otherwise, another easy way to install all the necessary packages is
to use Continuum Analytics' [http://docs.continuum.io/anaconda/install.html](Anaconda).