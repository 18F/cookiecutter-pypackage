{% set is_open_source = cookiecutter.open_source_license != 'Not open source' -%}

# {{ cookiecutter.project_name }}

{% if is_open_source %}
<a href="https://pypi.python.org/pypi/{{ cookiecutter.project_slug }}">
  <img src="https://img.shields.io/pypi/v/{{ cookiecutter.project_slug }}.svg"
  alt="PyPI shield">
</a>

<a href="https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}">
  <img src="https://img.shields.io/travis/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.svg"
  alt="Travis shield">
</a>

<a href="https://{{ cookiecutter.project_slug | replace("_", "-") }}.readthedocs.io/en/latest/?badge=latest ">
  <img src=https://readthedocs.org/projects/{{ cookiecutter.project_slug | replace("_", "-") }}/badge/?version=latest"
  alt="ReadTheDocs shield">
</a>

{%- endif %}

<a href="https://pyup.io/repos/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/">
  <img src="https://pyup.io/repos/github/{{ cookiecutter.github_username }}/cookiecutter-django/shield.svg"
  alt="Updates">
</a>

{{ cookiecutter.project_short_description }}

{% if is_open_source %}
* Documentation: https://{{ cookiecutter.project_slug | replace("_", "-") }}.readthedocs.io.
{% endif %}

## Features

* TODO

## Credits

This package was created with [Cookiecutter](https://github.com/audreyr/cookiecutter)
and the [18F/cookiecutter-pypackage](https://github.com/audreyr/cookiecutter-pypackage)
project template.

## Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
