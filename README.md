# build

[![CI](https://github.com/pypa/build/workflows/check/badge.svg)](https://github.com/pypa/build/actions)
[![codecov](https://codecov.io/gh/pypa/build/branch/master/graph/badge.svg)](https://codecov.io/gh/pypa/build)
[![Documentation Status](https://readthedocs.org/projects/pypa-build/badge/?version=latest)](https://pypa-build.readthedocs.io/en/latest/?badge=latest)
[![PyPI version](https://badge.fury.io/py/build.svg)](https://pypi.org/project/build/)

A simple, correct PEP517 package builder.

See the [documentation](https://pypa-build.readthedocs.io/en/latest/) for more information.

### Installation

`build` can be installed via `pip` or an equivalent via:

```
$ pip install build
```

### Usage

```bash
python -m build --sdist --wheel .
```

This will build the package in an isolated environment, generating a
source-distribution and wheel in the directory `dist/`.
See the [documentation](https://pypa-build.readthedocs.io/en/latest/) for full information.

### Code of Conduct

Everyone interacting in the build's codebase, issue trackers, chat rooms, and mailing lists is expected to follow
the [PSF Code of Conduct].

[psf code of conduct]: https://github.com/pypa/.github/blob/main/CODE_OF_CONDUCT.md
