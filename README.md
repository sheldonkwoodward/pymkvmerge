# pymkv
[![PyPI Version](https://img.shields.io/pypi/v/pymkv.svg)](https://pypi.python.org/pypi/pymkv)
[![License](https://img.shields.io/github/license/sheldonkwoodward/pymkv.svg)](https://github.com/sheldonkwoodward/pymkv/LICENSE.txt)
[![Code Quality](https://api.codacy.com/project/badge/Grade/e1fe077d95f74a5886c557024777c26c)](https://api.codacy.com/project/badge/Grade/e1fe077d95f74a5886c557024777c26c)

pymkv is a Python wrapper for mkvmerge. It provides support for muxing, splitting, linking, chapters, tags, and attachments through the use of mkvmerge.

## About pymkv
pymkv is a Python 3 library for manipulating MKV files with mkvmerge. Previously, I was constructing mkvmerge commands manually. They were becoming overly complex and unmanageable. To remedy this, I decided to write this library to make mkvmerge more scriptable and easier to use. Please open new issues for any bugs you find, support is greatly appreciated!

## Installation
mkvmerge must be installed on your computer. It is recommended to add it to your \$PATH variable but a different path can be manually specified. mkvmerge can be found and downloaded from [here] or in most package managers.

To install pymkv from PyPI, use the following command:

    $ pip install pymkv

You can also clone the repo and run the following command in the project root to edit the source code:

    $ pip install -e .

## Documentation
The documentation for pymkv can be found in the [here](https://pymkv.shel.dev/).
