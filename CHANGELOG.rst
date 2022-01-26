
Changelog
=========

0.0.1 (2022-01-26)
------------------

* Added ``hexed --version`` command line option
    * Versioning now based on setuptools-scm integration

* Completed configuration for CI integration
    * Currently utilizing CircleCI to learn about it
    * GitHub seems to have its own CI via workflows that are also being used

* Completed working ``tox`` testing configuration

* Flake no longer tests everything in site-packages
    * Using ``extend-exclude`` option to ignore ``.tox`` and ``venv`` environments

0.0.0 (2022-01-22)
------------------

* First release on PyPI.
