pysha256
========

A pure-Python sha256 implementation, derived from [Thom Dixon's pysha2](https://github.com/thomdixon/pysha2). It should be compatible with versions of Python 2.3 and newer. pysha2 can be used as a standalone script or as a Python module. (However, those interested in using it as a Python module should look at using pysha2 instead, which is more flexible.)

Usage
-----

```sh
$ pysha2 path_to_file
```

Why?
----

I needed to calculate hashes on a system that only has Python 2.3 available, which doesn't include any way to calculate sha256 hashes builtin.
