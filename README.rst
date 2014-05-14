===================
chronotope-buildout
===================

This is the buildout configuration package for the **Chronotope** Project.


Installation
============

Checkout this package with git::

    git@github.com:rnixx/chronotope-buildout.git

Create virtual environment and bootstrap installation::

    virtualenv --no-site-packages env
    ./env/bin/python bootstrap.py -c dev.cfg
    ./bin/buildout -c dev.cfg


Development and Testing
=======================

Running tests::

    ./bin/test

Start application::

    ./bin/paster serve dev.ini


Contributors
============

- Robert Niederreiter

- Holger Schwetter

- Leuphana Universität Lüneburg
