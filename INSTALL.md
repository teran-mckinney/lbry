Prerequisites
-------------

To use the LBRYWallet, which enables spending and accepting LBRYcrds in exchange for data, the
LBRYcrd application (insert link to LBRYcrd website here) must be installed and running. If
this is not desired, the testing client can be used to simulate trading points, which is
built into LBRYnet.

on Ubuntu:

```
sudo apt-get install libgmp3-dev build-essential python-dev python-pip
```

Getting the source
------------------

Don't you already have it?

Setting up the environment
--------------------------

It's recommended that you use a virtualenv

```
sudo apt-get install python-virtualenv
cd <source base directory>
virtualenv .
source bin/activate
```

(to deactivate the virtualenv, enter 'deactivate')

```
python setup.py install
```

this will install all of the libraries and a few applications

For running the file sharing application, see [RUNNING](RUNNING.md)
