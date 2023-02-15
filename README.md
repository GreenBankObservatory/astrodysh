# astrodysh

astrodysh!

## Installation

astrodysh requires Python 3.8+. Once you are in a suitable environment, simply:

```bash
# Currently available only via GBO's private PyPI repository
$ pip install pyspeckit --extra-index-url http://pypi.gb.nrao.edu/simple
```

## Development

If you are working on astrodysh itself, here's how to get your environment set up

First, you'll need `hatch` installed. The "proper" way to do that is via pipx:

```bash
$ pipx install hatch
```

But you can also manage your virtual environment entirely yourself:

```bash
$ python3.8 -m venv /path/to/venvs/astrodysh-3.8
$ source /path/to/venvs/astrodysh-3.8/bin/activate
$ pip install hatch
```

Once you have `hatch`, simply:

```
$ pip install -e .
```

To validate your virtual environment, you can run the tests:

```bash
$ pytest
```

You can run astrodysh CLI via:


```bash
$ astrodysh --help
```
