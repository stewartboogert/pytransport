# pyTransport

A python package containing both utilities for processing and analysing TRANSPORT output.

## Authors

W. Shields

Currently maintained and developed by:

* Will Shields          <william.shields@rhul.ac.uk>
* Jochem Snuverink      <jochem.snuverink@psi.ch>

## Setup

From within the pybdsim root directory:

$ make install

or for development:

$ make develop


```python
$ python
>>> import pytransport
>>> a = pytransport.Reader.GetOptics("FOR002.DAT")
>>> plot(a.S(), a.Sigma_X())
```
