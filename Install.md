# Installation and Testing #

## Checkout ##
```
$ svn checkout https://python-multiprocessing.googlecode.com/svn/trunk python-multiprocessing
```

## Compilation and testing under Python 2.5 ##

```
$ cd python-multiprocessing
$ make
$ make test
$ make examples
```

## Compilation and testing with other versions of Python ##

```
$ cd python-multiprocessing
$ make test PYTHON=python2.4
$ make test PYTHON=python2.6
```