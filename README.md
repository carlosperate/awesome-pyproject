# Awesome pyproject.toml [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Link Checker GH Action Status](https://github.com/carlosperate/awesome-pyproject/workflows/Check%20Links/badge.svg)](http://github.com/carlosperate/awesome-pyproject/actions?workflow=Check+Links)

![logo](https://repository-images.githubusercontent.com/226840558/aff71800-2fd4-11ea-99ed-8e6a645dd5fe)

`pyproject.toml` is a new configuration file defined in
[PEP 518](https://www.python.org/dev/peps/pep-0518/), expanded in
[PEP 621](https://www.python.org/dev/peps/pep-0621/) and 
[PEP 660](https://www.python.org/dev/peps/pep-660/). It is design to store
build system requirements, but it can also store any tool configuration for your
Python project, possibly replacing the need for `setup.cfg` or other
tool-specific files.

- [PEP 518 -- File specification](https://www.python.org/dev/peps/pep-0518/#specification).
- [PEP 621 -- Storing project metadata in pyproject.toml](https://www.python.org/dev/peps/pep-0621/#specification)
- [PEP 660 -- Editable installs for pyproject.toml based builds (wheel based)](https://peps.python.org/pep-0660/)

We think `pyproject.toml` is pretty awesome, so this
[awesome list](https://github.com/topics/awesome-list) contains projects already
using it, or discussing its inclusion.

Do you know of any other project not included here? Please
[submit a PR](contributing.md)!


## Contents

- [Testing](#testing)
- [Code Formatting](#code-formatting)
- [Code Analysis](#code-analysis)
- [Packaging & Project Management](#packaging--project-management)
- [Project Templates](#project-templates)
- [Other Tools](#other-tools)
- [Articles](#articles)
- [Open PEPs](#open-peps)
- [Projects discussing the use of pyproject.toml](#projects-discussing-the-use-of-pyprojecttoml)


## Testing

- [Coverage.py](https://coverage.readthedocs.io/en/latest/config.html) - Code coverage measurement for Python.
- [ptr](https://github.com/facebookincubator/ptr#pyprojecttoml) - Python Test Runner (ptr) was born to run tests in an opinionated way, within arbitrary code repositories.
- [pytest](https://docs.pytest.org/en/latest/reference/customize.html#pyproject-toml) - A testing framework that makes it easy to write small tests, yet scales to support complex functional testing.
- [pytest-env](https://github.com/pytest-dev/pytest-env) - A pytest plugin that enables you to set environment variables in a pyproject.toml file.
- [Tox](https://tox.readthedocs.io/en/3.14.2/example/basic.html#pyproject-toml-tox-legacy-ini) - A generic virtualenv manager to run test in different environments.
- [Ward](https://ward.readthedocs.io/en/latest/guide/pyproject.toml.html) - A modern Python test framework designed to help you find and fix flaws faster.


## Code Formatting

- [autoflake](https://github.com/PyCQA/autoflake) - Removes unused imports and unused variables as reported by pyflakes.
- [autoimport](https://lyz-code.github.io/autoimport/) - Automatically add missing imports and remove unused imports.
- [autopep8](https://github.com/hhatto/autopep8/blob/master/README.rst#pyproject-toml) - A tool that automatically formats Python code to conform to the PEP 8 style guide.
- [Black](https://black.readthedocs.io/en/stable/usage_and_configuration/the_basics.html#configuration-via-a-file) - The uncompromising Python code formatter.
- [Blue](https://blue.readthedocs.io/en/latest/) - The slightly less uncompromising Python code formatter.
- [Darker](https://github.com/akaihola/darker#customizing-darker-black-and-isort-behavior) - Apply black reformatting to Python files only in regions changed since a given commit.
- [flake8-isort](https://github.com/gforcada/flake8-isort/commit/701995ab1f401e6f64c58ce2cb58756216d2e8a2) - flake8 plugin that integrates isort.
- [isort](https://pycqa.github.io/isort/docs/configuration/options) - A Python utility / library to sort imports alphabetically, and automatically separated into sections.
- [pyproject-fmt](https://pyproject-fmt.readthedocs.io) - Apply a consistent format to your pyproject.toml file with comment support.
- [YAPF](https://github.com/google/yapf#excluding-files-from-formatting-yapfignore-or-pyprojecttoml) - A formatter for Python files.


## Code Analysis

- [Bandit](https://bandit.readthedocs.io/en/latest/config.html) - A tool designed to find common security issues in Python code.
- [deptry](https://github.com/fpgmaas/deptry) - A command line tool to check for issues with dependencies in a Python project, such as obsolete or missing dependencies.
- [FlakeHell](https://flakehell.readthedocs.io/config.html) - Flake8 wrapper to make it nice, legacy-friendly, configurable.
- [flake8-pyproject](https://pypi.org/project/Flake8-pyproject/) - Plugin for Flake8 that reads configuration from pyproject.toml and injects the config into Flake8
- [import-linter](https://import-linter.readthedocs.io/en/stable/usage.html) - Import Linter defines and enforces rules for the imports within and between Python packages.
- [interrogate](https://interrogate.readthedocs.io/en/latest/#other-usage) - Interrogate a codebase for docstring coverage.
- [Mypy](https://mypy.readthedocs.io/en/latest/config_file.html#using-a-pyproject-toml-file) - An optional static type checker for Python (PEP 484).
- [Nitpick](https://nitpick.readthedocs.io/en/latest/configuration.html) - Flake8 plugin to enforce the same tool configuration (flake8, isort, mypy, Pylint...) across multiple Python projects.
- [pydocstyle](https://www.pydocstyle.org/en/stable/usage.html#configuration-files) - A static analysis tool for checking compliance with Python docstring conventions.
- [Pylint](http://pylint.pycqa.org/en/latest/user_guide/run.html?highlight=pyproject#command-line-options) - A tool that checks for errors in Python code, tries to enforce a coding standard and looks for code smells.
- [Pyright](https://github.com/microsoft/pyright/blob/1.1.200/docs/configuration.md#sample-pyprojecttoml-file) - Static type checker for Python.
- [pytest-pylint](https://github.com/carsongee/pytest-pylint/pull/107) - A pytest plugin for running pylint against your codebase.
- [Refurb](https://github.com/dosisod/refurb) - A tool for refurbishing and modernizing Python codebases.
- [Robocop](https://robocop.readthedocs.io/en/stable/configuration.html#pyproject-toml-or-toml-configuration-file) - Tool for static code analysis of Robot Framework language.
- [rstcheck](https://rstcheck.readthedocs.io/en/latest/usage/config/#toml-format) - Checks syntax of reStructuredText and code blocks nested within it.
- [Ruff](https://beta.ruff.rs/docs/configuration/#pyprojecttoml-discovery) - An extremely fast Python linter, written in Rust.
- [Unimport](https://github.com/hakancelik96/unimport/blob/master/README.md#configuring-unimport) - Detects unused python libraries.
- [validate-pyproject](https://validate-pyproject.readthedocs.io) - A command line tool and Python library for validating pyproject.toml files based on JSON Schema, and includes checks for PEP 517, PEP 518 and PEP 621.
- [Vulture](https://github.com/jendrikseipp/vulture/blob/master/README.md#configuration) - Finds unused code in Python programs.
- [wemake-python-styleguide](https://wemake-python-styleguide.readthedocs.io/en/latest/pages/usage/integrations/flakeheaven.html) - The strictest and most opinionated python linter ever!


## Packaging & Project Management

- [BeeWare Briefcase](https://briefcase.readthedocs.io/en/latest/reference/configuration.html) - Tools to support converting a Python project into a standalone native application.
- [check-wheel-contents](https://github.com/jwodder/check-wheel-contents) - Check your wheels have the right contents.
- [DepHell](https://dephell.readthedocs.io/config.html) - Project management for Python. Manage packages: convert between formats, lock, install, resolve, isolate, test, build graph, show outdated, audit. Manage venvs, build package, bump version.
- [FawltyDeps](https://github.com/tweag/FawltyDeps) - Find undeclared and unused dependencies in your Python project. Verify that your declared dependencies (in `pyproject.toml` or elsewhere) match what you actually `import` in your code.
- [Flit](https://flit.readthedocs.io/en/stable/pyproject_toml.html) - A simple way to put Python packages and modules on PyPI.
- [Hatch](https://hatch.pypa.io/latest/config/metadata/) - Modern, extensible Python project manager.
- [Maturin](https://github.com/PyO3/maturin/blob/main/README.md#python-metadata) - Build and publish crates with pyo3, rust-cpython and cffi bindings as well as rust binaries as python packages.
- [PDM](https://pdm.fming.dev/latest/pyproject/pep621/) - A modern Python package manager with PEP 582 support.
- [pip](https://pip.pypa.io/en/stable/reference/pip/#pep-517-and-518-support) - The package installer for Python. You can use pip to install packages from the Python Package Index and other indexes.
- [Poetry](https://python-poetry.org/docs/pyproject/) - A tool for dependency management and packaging in Python. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you.
- [Pyflow](https://github.com/David-OConnor/pyflow) - An installation and dependency system for Python.
- [setuptools](hhttps://setuptools.pypa.io/en/latest/userguide/pyproject_config.html) - Easily download, build, install, upgrade, and uninstall Python packages.
- [setuptools_scm](https://github.com/pypa/setuptools_scm) - Handles managing your Python package versions in SCM metadata instead of declaring them as the version argument or in a SCM managed file.


## Project Templates

Python project templates or project generators supporting `pyproject.toml`.

- [cookiecutter-poetry](https://github.com/fpgmaas/cookiecutter-poetry) - A modern cookiecutter template for Python projects that use Poetry for their dependency management.
- [cookiecutter-pylibrary](https://github.com/ionelmc/cookiecutter-pylibrary) - Cookiecutter template for a Python python library.
- [Hypermodern Cookiecutter](https://github.com/cjolowicz/cookiecutter-hypermodern-python) - Cookiecutter template for a Python package based on the [Hypermodern Python](https://cjolowicz.github.io/posts/hypermodern-python-01-setup/) article series.
- [Jace's Python Template](https://github.com/jacebrowning/template-python) - A template for new Python libraries.
- [Poetry Cookiecutter](https://github.com/radix-ai/poetry-cookiecutter) - A modern Cookiecutter template for scaffolding Python packages and apps.
- [PyPA Sample Project](https://github.com/pypa/sampleproject) - A sample project that exists for PyPUG's "Tutorial on Packaging and Distributing Projects".
- [PyScaffold](https://github.com/pyscaffold/pyscaffold) - Python project template generator with batteries included.
- [Python Packages Project Generator](https://github.com/TezRomacH/python-package-template) - Cookiecutter template with state-of-the-art libraries and best development practices for Python.
- [Tyrannosaurus](https://github.com/dmyersturnbull/tyrannosaurus) - An opinionated, 2021+ Python template and project generator with many integrations and an automated CI/CD workflow triggered only through Git and GitHub.
- [wemake-django-template](https://github.com/wemake-services/wemake-django-template) - Bleeding edge django template focused on code quality and security.
- [wemake-python-package](https://github.com/wemake-services/wemake-python-package) - Bleeding edge cookiecutter template to create new python packages.


## Other Tools

- [Autohooks](https://github.com/greenbone/autohooks/blob/master/README.md#1-choosing-an-autohooks-mode) - Library for managing git hooks.
- [Commitizen](https://commitizen-tools.github.io/commitizen/config/) - Create commiting rules for projects, auto bump versions and auto changelog generation.
- [datamodel-code-generator](https://koxudaxi.github.io/datamodel-code-generator/pyproject_toml/) - Creates Pydantic data-model code from OpenAPI/JSON Schema files.
- [django-pyproject](https://github.com/Ceterai/django-pyproject) - Django package to store some or all of your settings in your pyproject.toml file.
- [ini2toml](https://ini2toml.readthedocs.io/en/latest/setuptools_pep621.html) - Automatically translates .ini/.cfg files into TOML.
- [Poe the Poet](https://github.com/nat-n/poethepoet#define-tasks-in-your-pyprojecttoml) - A task runner that works well with Poetry.
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


## Open PEPs

Python Enhancement Proposals (PEPs) still under consideration related to pyproject.toml.

- [PEP 725 – Specifying external dependencies in pyproject.toml](https://peps.python.org/pep-0725/)
- [PEP 735 – Dependency Groups in pyproject.toml](https://peps.python.org/pep-0735/)

### Rejected/Withdrawn/Superseded

- [PEP 631 – Dependency specification in pyproject.toml based on PEP 508](https://www.python.org/dev/peps/pep-0631/)
- [PEP 633 – Dependency specification in pyproject.toml using an exploded TOML table](https://www.python.org/dev/peps/pep-0633/)
- [PEP 650 – Specifying Installer Requirements for Python Projects](https://www.python.org/dev/peps/pep-0650/)
- [PEP 665 – A file format to list Python dependencies for reproducibility of an application](https://peps.python.org/pep-0665/)


## Projects discussing the use of `pyproject.toml`

Some project are still considering the adoption of the `pyproject.toml` file.
These entries link directly to the project discussion.

- [Alembic](https://github.com/sqlalchemy/alembic/issues/708) - A database migrations tool for SQLAlchemy.
- [AWS SAM](https://github.com/awslabs/aws-sam-cli/issues/1366) - CLI tool to build, test, debug, and deploy Serverless applications using AWS SAM.
- [Briefcase Bootstrap Template](https://github.com/beeware/briefcase-template/pull/16) - A template for starting a Python app that will be deployed using briefcase.
- [bumpversion](https://github.com/peritus/bumpversion/issues/192) - Version-bump your software with a single command.
  - [bump2version](https://github.com/c4urself/bump2version/issues/42) - An interim fork with the intent to merge back to the original project.
- [Dependency Parser](https://github.com/pyupio/dparse/issues/36) - A parser for Python dependency files.
- [flake8](https://github.com/PyCQA/flake8/issues/234) - A python tool that glues together pep8, pyflakes, mccabe, and third-party plugins to check the style and quality of some python code.
- [gitlint](https://github.com/jorisroovers/gitlint/issues/115) - Linting for your git commit messages.
- [Invoke](https://github.com/pyinvoke/invoke/issues/537) - Library for managing shell-oriented subprocesses and organizing executable Python code into CLI-invokable tasks.
- [mach-nix](https://github.com/DavHau/mach-nix/issues/14) - Create highly reproducible python environments.
- [nose2](https://github.com/nose-devs/nose2/issues/452) - The successor to nose. Its purpose is to extend unittest to make testing nicer and easier to understand.
- [prospector](https://github.com/PyCQA/prospector/issues/376) - A tool to analyse Python code and output information about errors, potential problems, convention violations and complexity.
- [pycodestyle](https://github.com/PyCQA/pycodestyle/issues/813) - A tool to check your Python code against some of the style conventions in PEP 8.
- [pyenv](https://github.com/pyenv/pyenv/issues/1233) - Simple Python version management.
- [pytest-benchmark](https://github.com/ionelmc/pytest-benchmark/issues/26) - A pytest fixture for benchmarking code.
- [Pylama](https://github.com/klen/pylama/issues/171) - Code audit tool for Python and JavaScript. Pylama wraps these tools: pycodestyle, pydocstyle, PyFlakes, Mccabe, Pylint, Radon, gjslint, eradicate, mypy.
- [PyOxidizer](https://github.com/indygreg/PyOxidizer/issues/93) - A modern Python application packaging and distribution tool.
- [pypyr](https://github.com/pypyr/pypyr/discussions/232) - Task-runner cli & api for automation pipelines. Automate anything by combining commands, different scripts in different languages & applications into one pipeline process.
- [pytype](https://github.com/google/pytype/issues/645) - A static type analyzer for Python code.
- [pyup](https://github.com/pyupio/pyup/issues/332) - tool to update your project's dependencies on GitHub. Runs on pyup.io, comes with a command line interface.
- [Radon](https://github.com/rubik/radon/issues/220) - A Python tool that computes various metrics from the source code.
- [readthedocs.org](https://github.com/readthedocs/readthedocs.org/issues/7065) - Read the Docs hosts documentation for the open source community.
- [Spack](https://github.com/spack/spack/issues/6629) - A flexible package manager that supports multiple versions, configurations, platforms, and compilers.
- [zest.releaser](https://github.com/zestsoftware/zest.releaser/issues/295) - Python software releasing made easy and repeatable.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighbouring rights to this work.
