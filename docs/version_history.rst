.. _ch-version-history:

.. module:: best
   :noindex:

Version History
===============

1.0
---
Initial release by `Andrew Straw <https://github.com/strawlab/best>`_.
This version supported Python 2.7, Matplotlib 2.2, and PyMC.

2.0.0
-----
Changes from version 1.0:

 - Upgrade to Python 3.5, PyMC3, and Matplotlib 3.0.0.
 - :ref:`Model version 2 <sec-model-v2>`.
 - Introduction of object-oriented API.
 - Changes in plot appearance.

2.0.2
-----

 - Fix: Automatically install requirements
 - Fix: Allow PyMC3 versions beyond 3.10.

2.0.4
-----

 - Required Python version is min. 3.7, as `3.6 is not officially supported anymore <https://devguide.python.org/#status-of-python-branches>`_ and dependencies fail to be installed on 3.5.
 - Fix an error in :func:`plot_posterior` when ``ax`` argument is ``None``.
 - Fix import-time error when NumPy >=1.22.0 installed.

2.0.5
-----

 - Fixed issue with "TypeError: summary() got an unexpected keyword argument 'alpha'" (`issue #6 <https://github.com/treszkai/best/issues/6>`_)
