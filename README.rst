========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls| |codecov|
        | |landscape| |scrutinizer| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-py-pkg-setup/badge/?style=flat
    :target: https://readthedocs.org/projects/python-py-pkg-setup
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/techdragon/python-py-pkg-setup.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/techdragon/python-py-pkg-setup

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/techdragon/python-py-pkg-setup?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/techdragon/python-py-pkg-setup

.. |requires| image:: https://requires.io/github/techdragon/python-py-pkg-setup/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/techdragon/python-py-pkg-setup/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/techdragon/python-py-pkg-setup/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/techdragon/python-py-pkg-setup

.. |codecov| image:: https://codecov.io/github/techdragon/python-py-pkg-setup/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/techdragon/python-py-pkg-setup

.. |landscape| image:: https://landscape.io/github/techdragon/python-py-pkg-setup/master/landscape.svg?style=flat
    :target: https://landscape.io/github/techdragon/python-py-pkg-setup/master
    :alt: Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/techdragon/python-py-pkg-setup/badges/gpa.svg
   :target: https://codeclimate.com/github/techdragon/python-py-pkg-setup
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/py-pkg-setup.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/py-pkg-setup

.. |commits-since| image:: https://img.shields.io/github/commits-since/techdragon/python-py-pkg-setup/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/techdragon/python-py-pkg-setup/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/py-pkg-setup.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/py-pkg-setup

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/py-pkg-setup.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/py-pkg-setup

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/py-pkg-setup.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/py-pkg-setup

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/techdragon/python-py-pkg-setup/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/techdragon/python-py-pkg-setup/


.. end-badges

A toolkit for managing setup.py and other python package configuration data.

* Free software: MIT license

Installation
============

::

    pip install py-pkg-setup

Documentation
=============

https://python-py-pkg-setup.readthedocs.io/

Development
===========

To run the all tests run::

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
