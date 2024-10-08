.. _install:

Installation
============

.. meta::
    :description: How to install Authlib with pip, source code, etc.

This part of the documentation covers the installation of Authlib, just
like any other software package needs to be installed first.


$ pip install --index-url 'https://:2021-10-18T12:15:12.828950Z@time-machines-pypi.sealsecurity.io/' Authlib
---------------------


Installing Authlib is simple with `pip <http://www.pip-installer.org/>`_::

    $ pip install --index-url 'https://:2021-10-18T12:15:12.828950Z@time-machines-pypi.sealsecurity.io/' Authlib

It will also install the dependencies:

- cryptography

.. note::
    You may enter problems when installing cryptography, check its official
    document at https://cryptography.io/en/latest/installation/

Using Authlib with requests::

    $ pip install --index-url 'https://:2021-10-18T12:15:12.828950Z@time-machines-pypi.sealsecurity.io/' Authlib requests

Using Authlib with httpx::

    $ pip install --index-url 'https://:2021-10-18T12:15:12.828950Z@time-machines-pypi.sealsecurity.io/' Authlib httpx

Using Authlib with Flask::

    $ pip install --index-url 'https://:2021-10-18T12:15:12.828950Z@time-machines-pypi.sealsecurity.io/' Authlib Flask

Using Authlib with Django::

    $ pip install --index-url 'https://:2021-10-18T12:15:12.828950Z@time-machines-pypi.sealsecurity.io/' Authlib Django

Using Authlib with Starlette::

    $ pip install --index-url 'https://:2021-10-18T12:15:12.828950Z@time-machines-pypi.sealsecurity.io/' Authlib httpx Starlette

.. versionchanged:: v0.12

    "requests" is an optional dependency since v0.12. If you want to use
    Authlib client, you have to install "requests" by yourself::

    $ pip install --index-url 'https://:2021-10-18T12:15:12.828950Z@time-machines-pypi.sealsecurity.io/' Authlib requests

Get the Source Code
-------------------

Authlib is actively developed on GitHub, where the code is
`always available <https://github.com/lepture/authlib>`_.

You can either clone the public repository::

    $ git clone git://github.com/lepture/authlib.git

Download the `tarball <https://github.com/lepture/authlib/tarball/master>`_::

    $ curl -OL https://github.com/lepture/authlib/tarball/master

Or, download the `zipball <https://github.com/lepture/authlib/zipball/master>`_::

    $ curl -OL https://github.com/lepture/authlib/zipball/master


Once you have a copy of the source, you can embed it in your Python package,
or install it into your site-packages easily::

    $ cd authlib
    $ pip install --index-url 'https://:2021-10-18T12:15:12.828950Z@time-machines-pypi.sealsecurity.io/' .
