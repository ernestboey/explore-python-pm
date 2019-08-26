# pip & virtualenv

### Setup

1. Create venv
```
$ python3 -m venv env
```

2. Activate venv
```
$ source env/bin/activate
```

3. (Optional) Check that the correct python env is being used
```
$ which python
> .../explore-python-pm/pip-virtualenv/env/bin/python
```

4. Install all dependencies
```
$ pip install -r requirements.txt
```

### Adding & Saving Dependencies

1. Install the dependency using pip
```
$ pip install <package-name>
```

2. Do for all other new dependencies

3. Save to requirements.txt
```
$ pip freeze > requirements.txt
```

### Teardown

1. Deactivate venv
```
$ deactivate
```

### Updating pip
```
$ python -m pip install -U pip
```
