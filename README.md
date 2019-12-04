# Distributing python packages protected with Cython

This is a sample application for demonstrating how to protect app source code and distribute package. All magic is in the ``setup.py`` file.

## Set up environment

```
$ virtualenv .venv --python=python3.6
$ source .venv/bin/activate
$ pip install Cython
``` 

## Build package

```
$ python setup.py build_ext --inplace
$ python setup.py bdist_wheel
```
