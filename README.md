# racpy

bogus update

Python utils

## Release to pypi

Ref. https://twine.readthedocs.io/en/stable/index.html

Build...

```
python -m build
```

Upload (Test PyPi)...

```
TWINE_PASSWORD=XXX twine upload --repository testpypi dist/*
```

where `TWINE_PASSWORD` is the API key obtained at 

Or, add credentials to file `~/.pypirc`...

```
[testpypi]
  username = __token__
  password = XXX
```
