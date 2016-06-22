![swimlane](https://raw.githubusercontent.com/swimlane/swimlane-python/master/docs/logo.png)

Python driver for the [Swimlane](http://www.swimlane.com) API

![version](https://img.shields.io/pypi/v/swimlane.svg) ![py-versions](https://img.shields.io/pypi/pyversions/swimlane.svg) ![py-impl](https://img.shields.io/pypi/implementation/swimlane.svg) ![travis](https://travis-ci.org/swimlane/swimlane-python.svg?branch=master) [![Code Climate](https://codeclimate.com/github/swimlane/swimlane-python/badges/gpa.svg)](https://codeclimate.com/github/swimlane/swimlane-python) [![Test Coverage](https://codeclimate.com/github/swimlane/swimlane-python/badges/coverage.svg)](https://codeclimate.com/github/swimlane/swimlane-python/coverage)

## Using

Install `swimlane` via pip:

```
$ pip install swimlane
```

or download [release package](https://github.com/Swimlane/swwimlane-python/releases). See the  [documentation](http://swimlane-python.readthedocs.org) for more information.

## Developing

### Toolchain

* [pyenv](https://github.com/yyuu/pyenv)
    * [pyenv-virtualenv](https://github.com/yyuu/pyenv-virtualenv)
    * [pyenv-virtualenvwrapper](https://github.com/yyuu/pyenv-virtualenvwrapper)
* [virtualenv](https://virtualenv.readthedocs.org/en/latest/)
* [virtualenvwrapper](http://virtualenvwrapper.readthedocs.org/)

### Initial Setup

Clone the repository, create a virtualenv, and install the requirements:

```
$ git clone git@github.com:swimlane/swimlane-python.git
$ cd swimlane-python
$ mkvirtualenv <YOUR_ENV_NAME>
$ pip install -r requirements.txt
```

Install `swimlane` locally in edit mode:

```
$ make local
```

Install all supported Pythons:

```
$ make pythons
```

### Tests

Run the tests:

```
$ make test
```

### Docs

Build the docs:

```
$ make docs
```

### Tox

Run `tox` as usual - keep in mind that everything in `requirements.txt` will
be installed in each virtualenv that Tox creates.

## Support
Visit http://support.swimlane.com to log bugs or feature requests
