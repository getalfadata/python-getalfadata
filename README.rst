========
Overview
========

Python API for Get Alfa Data

* Free software: BSD 2-Clause License

Installation
============

::

    pip install getalfadata

You can also install the in-development version with::

    pip install git+ssh://git@https://github.com/getalfadata/python-getalfadata.git/getalfadata/python-getalfadata.git@main

Documentation
=============


https://python-getalfadata.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
