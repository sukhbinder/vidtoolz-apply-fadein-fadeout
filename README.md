# vidtoolz-apply-fadein-fadeout

[![PyPI](https://img.shields.io/pypi/v/vidtoolz-apply-fadein-fadeout.svg)](https://pypi.org/project/vidtoolz-apply-fadein-fadeout/)
[![Changelog](https://img.shields.io/github/v/release/sukhbinder/vidtoolz-apply-fadein-fadeout?include_prereleases&label=changelog)](https://github.com/sukhbinder/vidtoolz-apply-fadein-fadeout/releases)
[![Tests](https://github.com/sukhbinder/vidtoolz-apply-fadein-fadeout/workflows/Test/badge.svg)](https://github.com/sukhbinder/vidtoolz-apply-fadein-fadeout/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/sukhbinder/vidtoolz-apply-fadein-fadeout/blob/main/LICENSE)

Apply fadein-fadeout effects on videos 

## Installation

First install [vidtoolz](https://github.com/sukhbinder/vidtoolz).

```bash
pip install vidtoolz
```

Then install this plugin in the same environment as your vidtoolz application.

```bash
vidtoolz install vidtoolz-apply-fadein-fadeout
```
## Usage

type ``vid fadeinout --help`` to get help



## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:
```bash
cd vidtoolz-apply-fadein-fadeout
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
python -m pytest
```
