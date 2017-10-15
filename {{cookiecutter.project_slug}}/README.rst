{% set is_open_source = cookiecutter.open_source_license != 'Not open source' -%}
{% for _ in cookiecutter.project_name %}={% endfor %}
{{ cookiecutter.project_name }}
{% for _ in cookiecutter.project_name %}={% endfor %}

.. image:: https://img.shields.io/pypi/v/{{ cookiecutter.project_slug }}.svg
   :target: https://pypi.python.org/pypi/{{ cookiecutter.project_slug }}
   :alt: PyPI status

.. image:: https://circleci.com/gh/18F/{{ cookiecutter.project_slug }}.svg?style=svg
   :target: https://circleci.com/gh/18F/{{ cookiecutter.project_slug }}
   :alt: CircleCI status

(get `codeclimate badges
https://codeclimate.com/github/18F/rdbms-subsetter/badges`_)

.. image:: https://gemnasium.com/badges/github.com/18F/{{ cookiecutter.project_slug }}.svg
   :target: https://gemnasium.com/github.com/18F/{{ cookiecutter.project_slug }}
   :alt: Gemnasium

{{ cookiecutter.project_short_description }}

* Documentation: https://{{ cookiecutter.project_slug | replace("_", "-") }}.readthedocs.io.

Features
--------

* TODO

Credits
---------

This package was created with Cookiecutter_ and the `18F/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`18F/cookiecutter-pypackage`: https://github.com/18F/cookiecutter-pypackage


Public domain
-------------

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.rst):

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.rst):

    This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the `CC0 1.0`_ Universal public domain dedication.

    All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.

.. _`CC 1.0`: https://creativecommons.org/publicdomain/zero/1.0/)
.. _`public domain`: LICENSE.md
.. _CONTRIBUTING: CONTRIBUTING.rst

