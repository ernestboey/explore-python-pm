# poetry

[poetry](https://github.com/sdispater/poetry)

## Installation

[Installation Guide](https://poetry.eustace.io/docs/)

## Usage

0. Ensure your `$ python` points to the right version (you can use pyenv)

1. Initialise project
```
$ poetry init
```

2. Install dependencies

If adding new dependencies:
```
$ poetry add request sqlalchemy
```

If installing from existing project
```
$ poetry install
```

3. (Optional) Update dependencies
```
$ poetry update [specific packages]
```

4. Run code
```
$ poetry run python poetry/main.py
```

* Virtualenv location was **~/Library/Caches/pypoetry/virtualenvs**

1. Remove virtualenv
```
$ poetry env info
$ poetry env remove python
$ poetry env info
```
