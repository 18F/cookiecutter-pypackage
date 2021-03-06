======================
Cookiecutter PyPackage
======================

.. image:: https://pyup.io/repos/github/audreyr/cookiecutter-pypackage/shield.svg
     :target: https://pyup.io/repos/github/18f/cookiecutter-pypackage/
     :alt: Updates

Cookiecutter_ template for an 18F Python package.  Forked from
https://github.com/audreyr/cookiecutter-pypackage/, with changes
to comply with 18F's practices.

* GitHub repo: https://github.com/18F/cookiecutter-pypackage/
* Documentation: https://cookiecutter-pypackage.readthedocs.io/

Features
--------

* Testing setup with ``unittest`` and ``python setup.py test`` or ``py.test``
* Tox_ testing: Setup to easily test for Python 2.6, 2.7, 3.3, 3.4, 3.5
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_
* Bumpversion_: Pre-configured version bumping with a single command
* Auto-release to PyPI_ when you push a new tag to master (optional)
* Command line interface using Click (optional)

.. _Cookiecutter: https://github.com/18f/cookiecutter

Build Status
-------------

Windows:

.. image:: https://ci.appveyor.com/api/projects/status/github/18f/cookiecutter-pypackage?branch=master&svg=true
    :target: https://ci.appveyor.com/project/18f/cookiecutter-pypackage/branch/master
    :alt: Windows build status on Appveyor

Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/18f/cookiecutter-pypackage.git

Then:

* Create a repo and put it there.
* Install the dev requirements into a virtualenv. (``pip install -r requirements_dev.txt``)
* Add the repo to your ReadTheDocs_ account + turn on the ReadTheDocs service hook.
* Release your package by pushing a new tag to master.
* Add a `requirements.txt` file that specifies the packages you will need for
  your project and their versions. For more info see the `pip docs for requirements files`_.
* Activate your project on `pyup.io`_.

.. _`pip docs for requirements files`: https://pip.pypa.io/en/stable/user_guide/#requirements-files

For more details, see the `cookiecutter-pypackage tutorial`_.

.. _`cookiecutter-pypackage tutorial`: https://cookiecutter-pypackage.readthedocs.io/en/latest/tutorial.html

License
-------

https://github.com/audreyr/cookiecutter-pypackage is licensed under the
BSD license.  The small modifications to it in this fork, as a work
of the United States Government, are under the
public domain within the United States.

Additionally, 18F waives copyright and related rights to its modifications
worldwide through the `CC0`_ 1.0 Universal public domain dedication.

.. _`CC0`: https://creativecommons.org/publicdomain/zero/1.0
