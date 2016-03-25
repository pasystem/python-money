# Introduction #

There are a few methods of installing python-money.  You can either download/checkout the project and use **setup.py**.  Or if you've installed [pip](http://www.pip-installer.org/en/latest/index.html) you can grab it from [PyPi](http://pypi.python.org/pypi) or straight out of the project repository.

## Using setup.py ##

First, either download the latest tarball from the [download page](http://code.google.com/p/python-money/downloads/list).

Extract the source with
```
tar -xzf python-money-XXX.tar.xzf
```

**OR**

Checkout the latest version from the project repository using SVN.
```
svn checkout http://python-money.googlecode.com/svn/trunk/ python-money
```

Then cd into the project directory
```
cd python-money
```

and just run setup.py
```
python setup.py install
```

## Using pip ##

If you have pip installed your can install from the PyPi repository

```
pip install python-money
```

or if you want the latest version, you can install directly from the project repository

```
pip install svn+http://python-money.googlecode.com/svn/trunk/
```

## Testing your installation ##

Open up a python shell and see you can import python-money classes

```
~$ python
>>> from money import Money
>>> Money(6, 'AUD')
AUD 6.0
```