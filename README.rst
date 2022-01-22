========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions|
        |
    * - package
      - | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-hexed/badge/?style=flat
    :target: https://python-hexed.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/thumdugger/python-hexed/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/thumdugger/python-hexed/actions

.. |commits-since| image:: https://img.shields.io/github/commits-since/thumdugger/python-hexed/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/thumdugger/python-hexed/compare/v0.0.0...main



.. end-badges

A playground package for exploring hex mapping as described at: https://www.redblobgames.com/grids/hexagons/

* Free software: BSD 2-Clause License

Installation
============

::

    pip install hexed

You can also install the in-development version with::

    pip install https://github.com/thumdugger/python-hexed/archive/main.zip


Documentation
=============


https://python-hexed.readthedocs.io/


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
