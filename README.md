# Awesome pyproject.toml [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Link Checker GH Action Status](https://github.com/carlosperate/awesome-pyproject/workflows/Check%20Links/badge.svg)](http://github.com/carlosperate/awesome-pyproject/actions?workflow=Check+Links)

![logo](https://repository-images.githubusercontent.com/226840558/aff71800-2fd4-11ea-99ed-8e6a645dd5fe)

`pyproject.toml` is a new configuration file defined in
[PEP 518](https://www.python.org/dev/peps/pep-0518/). It is design to store
build system requirements, but it can also store any tool configuration for your
Python project, possibly replacing the need for `setup.cfg` or other
tool-specific files.

- [PEP 518 file specification](https://www.python.org/dev/peps/pep-0518/#specification).

We think `pyproject.toml` is pretty awesome, so this
[awesome list](https://github.com/topics/awesome-list) contains projects already
using it, or discussing its inclusion.

Do you know of any other project not included here? Please
[submit a PR](contributing.md)!


## Contents

- [Testing](#testing)
- [Code Formatting](#code-formatting)
- [Code Analysis](#code-analysis)
- [Packaging](#packaging)
- [Project Templates](#project-templates)
- [Other Tools](#other-tools)
- [Articles](#articles)
- [Projects discussing the use of pyproject.toml](#projects-discussing-the-use-of-pyprojecttoml)


## Testing

- [Coverage.py](https://coverage.readthedocs.io/en/latest/config.html) - Code coverage measurement for Python.
- [Tox](https://tox.readthedocs.io/en/3.14.2/example/basic.html#pyproject-toml-tox-legacy-ini) - A generic virtualenv manager to run test in different environments.
- [Ward](https://wardpy.com/guide/config) - A modern Python test framework designed to help you find and fix flaws faster. 


## Code Formatting

- [autopep8](https://github.com/hhatto/autopep8/blob/master/README.rst#pyproject-toml) - A tool that automatically formats Python code to conform to the PEP 8 style guide.
- [Black](https://black.readthedocs.io/en/stable/pyproject_toml.html) - The uncompromising Python code formatter.
- [flake8-isort](https://github.com/gforcada/flake8-isort/commit/701995ab1f401e6f64c58ce2cb58756216d2e8a2) - flake8 plugin that integrates isort.
- [isort](https://timothycrosley.github.io/isort/) - A Python utility / library to sort imports alphabetically, and automatically separated into sections.


## Code Analysis

- [FlakeHell](https://flakehell.readthedocs.io/config.html) - Flake8 wrapper to make it nice, legacy-friendly, configurable.
- [Nitpick](https://nitpick.readthedocs.io/en/latest/config_files.html) - Flake8 plugin to enforce the same tool configuration (flake8, isort, mypy, Pylint...) across multiple Python projects.
- [Pylint](http://pylint.pycqa.org/en/latest/user_guide/run.html?highlight=pyproject#command-line-options) - A tool that checks for errors in Python code, tries to enforce a coding standard and looks for code smells.
- [pytest-pylint](https://github.com/carsongee/pytest-pylint/pull/107) - A pytest plugin for running pylint against your codebase.
- [Unimport](https://github.com/hakancelik96/unimport/blob/master/README.md#configuring-unimport) - Detects unused python libraries.
- [wemake-python-styleguide](https://wemake-python-stylegui.de/en/latest/pages/usage/integrations/flakehell.html) - The strictest and most opinionated python linter ever!


## Packaging

- [BeeWare Briefcase](https://github.com/beeware/briefcase/pull/266) - Tools to support converting a Python project into a standalone native application.
- [check-wheel-contents](https://github.com/jwodder/check-wheel-contents) - Check your wheels have the right contents.
- [DepHell](https://dephell.readthedocs.io/config.html) - Project management for Python. Manage packages: convert between formats, lock, install, resolve, isolate, test, build graph, show outdated, audit. Manage venvs, build package, bump version.
- [Flit](https://flit.readthedocs.io/en/stable/pyproject_toml.html) - A simple way to put Python packages and modules on PyPI.
- [pip](https://pip.pypa.io/en/stable/reference/pip/#pep-517-and-518-support) - The package installer for Python. You can use pip to install packages from the Python Package Index and other indexes.
- [Poetry](https://python-poetry.org/docs/pyproject/) - A tool for dependency management and packaging in Python. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you.
- [Pyflow](https://github.com/David-OConnor/pyflow) - An installation and dependency system for Python.
- [Maturin](https://github.com/PyO3/maturin/blob/master/Readme.md#pyprojecttoml) - Build and publish crates with pyo3, rust-cpython and cffi bindings as well as rust binaries as python packages.


## Project Templates

Python project templates or project generators supporting `pyproject.toml`.

- [cookiecutter-pylibrary](https://github.com/ionelmc/cookiecutter-pylibrary) - Cookiecutter template for a Python python library.
- [Jace's Python Template](https://github.com/jacebrowning/template-python) - A template for new Python libraries.
- [PyPA Sample Project](https://github.com/pypa/sampleproject) - A sample project that exists for PyPUG's "Tutorial on Packaging and Distributing Projects".
- [PyScaffold](https://github.com/pyscaffold/pyscaffold) - Python project template generator with batteries included.
- [wemake-django-template](https://github.com/wemake-services/wemake-django-template) - Bleeding edge django template focused on code quality and security.
- [wemake-python-package](https://github.com/wemake-services/wemake-python-package) - Bleeding edge cookiecutter template to create new python packages.


## Other Tools

- [Autohooks](https://github.com/greenbone/autohooks/blob/master/README.md#1-choosing-an-autohooks-mode) - Library for managing git hooks.
- [Commitizen](https://commitizen-tools.github.io/commitizen/config/) - Create commiting rules for projects, auto bump versions and auto changelog generation.
- [Poetrify](https://github.com/kk6/poetrify) - Convert a Pipfile (or requirements.txt) to pyproject.toml for Poetry.
- [poetry-setup](https://github.com/orsinium/poetry-setup) - Generate setup.py (setuptools) from pyproject.toml.
- [poetry-version](https://github.com/rominf/poetry-version) - Python library for extracting version from poetry pyproject.toml file.
- [Python License Checker](https://github.com/dhatim/python-license-check/pull/32) - Check python packages from requirement.txt/pyproject.toml and report issues.
- [Tartufo](https://tartufo.readthedocs.io/en/latest/configuration.html#configuration-via-file) - Searches through git repositories and their history for high entropy strings and secrets.
- [towncrier](https://github.com/twisted/towncrier) - A utility to produce useful, summarised news files for your project.
- [Vendy](https://github.com/di/vendy) - A tool for vendoring third-party packages into your project.
- [zsh-autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv/pull/117) - ZSH plugin to automatically switch python virtualenvs and Pipenvs as you move between directories.


## Articles

- [Clarifying PEP 518 (a.k.a. pyproject.toml)](https://snarky.ca/clarifying-pep-518/)
- [What the heck is pyproject.toml?](https://snarky.ca/what-the-heck-is-pyproject-toml/)


## Projects discussing the use of `pyproject.toml`

Some project are still considering the adoption of the `pyproject.toml` file.
These entries link directly to the project discussion.

- [AWS SAM](https://github.com/awslabs/aws-sam-cli/issues/1366) - CLI tool to build, test, debug, and deploy Serverless applications using AWS SAM.
- [Bandit](https://github.com/PyCQA/bandit/issues/550) - A tool designed to find common security issues in Python code.
- [Briefcase Bootstrap Template](https://github.com/beeware/briefcase-template/pull/16) - A template for starting a Python app that will be deployed using briefcase.
- [bumpversion](https://github.com/peritus/bumpversion/issues/192) - Version-bump your software with a single command.
  - [bump2version](https://github.com/c4urself/bump2version/issues/42) - An interim fork with the intent to merge back to the original project.
- [Dependency Parser](https://github.com/pyupio/dparse/issues/36) - A parser for Python dependency files.
- [flake8](https://gitlab.com/pycqa/flake8/issues/428) - A python tool that glues together pep8, pyflakes, mccabe, and third-party plugins to check the style and quality of some python code.
- [gitlint](https://github.com/jorisroovers/gitlint/issues/115) - Linting for your git commit messages.
- [Invoke](https://github.com/pyinvoke/invoke/issues/537) - Library for managing shell-oriented subprocesses and organizing executable Python code into CLI-invokable tasks.
- [Mypy](https://github.com/python/mypy/issues/5205) - An optional static type checker for Python (PEP 484).
- [nose2](https://github.com/nose-devs/nose2/issues/452) - The successor to nose. Its purpose is to extend unittest to make testing nicer and easier to understand.
- [prospector](https://github.com/PyCQA/prospector/issues/376) - A tool to analyse Python code and output information about errors, potential problems, convention violations and complexity.
- [pycodestyle](https://github.com/PyCQA/pycodestyle/issues/813) - A tool to check your Python code against some of the style conventions in PEP 8.
- [pyenv](https://github.com/pyenv/pyenv/issues/1233) - Simple Python version management.
- [pytest](https://github.com/pytest-dev/pytest/issues/1556) - A testing framework that makes it easy to write small tests, yet scales to support complex functional testing.
- [pytest-benchmark](https://github.com/ionelmc/pytest-benchmark/issues/26) - A pytest fixture for benchmarking code.
- [Pylama](https://github.com/klen/pylama/issues/171) - Code audit tool for Python and JavaScript. Pylama wraps these tools: pycodestyle, pydocstyle, PyFlakes, Mccabe, Pylint, Radon, gjslint, eradicate, mypy.
- [PyOxidizer](https://github.com/indygreg/PyOxidizer/issues/93) - A modern Python application packaging and distribution tool.
- [pyup](https://github.com/pyupio/pyup/issues/332) - tool to update your project's dependencies on GitHub. Runs on pyup.io, comes with a command line interface.
- [setuptools](https://github.com/pypa/setuptools/issues/1688) - Easily download, build, install, upgrade, and uninstall Python packages.
- [Spack](https://github.com/spack/spack/issues/6629) - A flexible package manager that supports multiple versions, configurations, platforms, and compilers.
- [Vulture](https://github.com/jendrikseipp/vulture/issues/164) - Finds unused code in Python programs.
- [YAPF](https://github.com/google/yapf/issues/708) - A formatter for Python files.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighbouring rights to this work.
