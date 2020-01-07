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
- [Other Tools](#other-tools)
- [Projects discussing the use of pyproject.toml](#projects-discussing-the-use-of-pyprojecttoml)


## Testing

- [Coverage.py](https://coverage.readthedocs.io/en/latest/config.html) - Code coverage measurement for Python.
- [Tox](https://tox.readthedocs.io/en/3.14.2/example/basic.html#pyproject-toml-tox-legacy-ini) - A generic virtualenv manager to run test in different environments.


## Code Formatting

- [autopep8](https://github.com/hhatto/autopep8/blob/master/README.rst#pyproject-toml) - A tool that automatically formats Python code to conform to the PEP 8 style guide.
- [Black](https://black.readthedocs.io/en/stable/pyproject_toml.html) - The uncompromising Python code formatter.
- [isort](https://timothycrosley.github.io/isort/) - A Python utility / library to sort imports alphabetically, and automatically separated into sections.


## Code Analysis

- [Pylint](http://pylint.pycqa.org/en/latest/user_guide/run.html?highlight=pyproject#command-line-options) - A tool that checks for errors in Python code, tries to enforce a coding standard and looks for code smells.


## Packaging

- [BeeWare Briefcase](https://github.com/beeware/briefcase/pull/266) - Tools to support converting a Python project into a standalone native application.
- [DepHell](https://dephell.readthedocs.io/config.html) - Project management for Python. Manage packages: convert between formats, lock, install, resolve, isolate, test, build graph, show outdated, audit. Manage venvs, build package, bump version.
- [Flit](https://flit.readthedocs.io/en/stable/pyproject_toml.html) - A simple way to put Python packages and modules on PyPI.
- [pip](https://pip.pypa.io/en/stable/reference/pip/#pep-517-and-518-support) - The package installer for Python. You can use pip to install packages from the Python Package Index and other indexes.
- [Poetry](https://python-poetry.org/docs/pyproject/) - A tool for dependency management and packaging in Python. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you.


## Other Tools

- [Poetrify](https://github.com/kk6/poetrify) - Convert a Pipfile (or requirements.txt) to pyproject.toml for Poetry. 
- [zsh-autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv/pull/117) - ZSH plugin to automatically switch python virtualenvs and Pipenvs as you move between directories.


## Projects discussing the use of `pyproject.toml`

Some project are still considering the adoption of the `pyproject.toml` file.
These entries link directly to the project discussion.

- [AWS SAM](https://github.com/awslabs/aws-sam-cli/issues/1366) - CLI tool to build, test, debug, and deploy Serverless applications using AWS SAM.
- [Bandit](https://github.com/PyCQA/bandit/issues/550) - A tool designed to find common security issues in Python code.
- [bumpversion](https://github.com/peritus/bumpversion/issues/192) - Version-bump your software with a single command.
  - [bump2version](https://github.com/c4urself/bump2version/issues/42) - An interim fork with the intent to merge back to the original project.
- [flake8](https://gitlab.com/pycqa/flake8/issues/428) - A python tool that glues together pep8, pyflakes, mccabe, and third-party plugins to check the style and quality of some python code.
- [gitlint](https://github.com/jorisroovers/gitlint/issues/115) - Linting for your git commit messages.
- [Invoke](https://github.com/pyinvoke/invoke/issues/537) - Library for managing shell-oriented subprocesses and organizing executable Python code into CLI-invokable tasks.
- [Mypy](https://github.com/python/mypy/issues/5205) - An optional static type checker for Python (PEP 484).
- [nose2](https://github.com/nose-devs/nose2/issues/452) - The successor to nose. Its purpose is to extend unittest to make testing nicer and easier to understand.
- [pycodestyle](https://github.com/PyCQA/pycodestyle/issues/813) - A tool to check your Python code against some of the style conventions in PEP 8.
- [pyenv](https://github.com/pyenv/pyenv/issues/1233) - Simple Python version management.
- [pytest](https://github.com/pytest-dev/pytest/issues/1556) - A testing framework that makes it easy to write small tests, yet scales to support complex functional testing.
- [pytest-benchmark](https://github.com/ionelmc/pytest-benchmark/issues/26) - A pytest fixture for benchmarking code.
- [pytest-pylint](https://github.com/carsongee/pytest-pylint/pull/107) - A pytest plugin for running pylint against your codebase.
- [PyOxidizer](https://github.com/indygreg/PyOxidizer/issues/93) - A modern Python application packaging and distribution tool.
- [setuptools](https://github.com/pypa/setuptools/issues/1688) - Easily download, build, install, upgrade, and uninstall Python packages.
- [Spack](https://github.com/spack/spack/issues/6629) - A flexible package manager that supports multiple versions, configurations, platforms, and compilers.
- [Vulture](https://github.com/jendrikseipp/vulture/issues/164) - Finds unused code in Python programs.
- [YAPF](https://github.com/google/yapf/issues/708) - A formatter for Python files.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighbouring rights to this work.
