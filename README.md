## Requirement

The linepy module only requires Python 3. You can download from [here](https://www.python.org/downloads/). 

## Installation

Installation is simple. It can be installed from pip using the following command:
```sh
$ pip install linepy
```
Or from the code:
```sh
$ python setup.py install
```

## Usage

```python
>>> from linepy import *
>>> line = LINE('EMAIL', 'PASSWORD')
>>> line.log("Auth Token : " + str(line.authToken))
```

## Updates

From pip using the following command:
```sh
$ pip install linepy --upgrade
```

