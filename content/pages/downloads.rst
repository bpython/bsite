Downloads
#########

:sort: 1
:save-as: downloads.html

The easiest way to get bpython is by installing it with pip, preferably in your
virtual environment.

.. code-block:: shell

  pip install bpython

There are several other ways of installing or getting the source to bpython as
well.

Release tarball
===============
The latest release for bpython is **0.19** and you can download it on our
`release page`_. You can find older releases here.

Git repository
==============
The development version is available with git; use the following command:

.. code-block:: shell

  git clone https://github.com/bpython/bpython/

If you get stuck, join #bpython on irc.freenode.net or send an email to the
mailing list (more info).

Packages
========
(Note that packages may be out of date so please try at least the latest release
if you have any problems before reporting bugs).

Debian
------
David Paleino maintains the bpython package. The package is included since
the release of squeeze. You can install it with:

.. code-block:: shell

  apt-get install bpython

Fedora
------
Terje Rosten has informed me that bpython is now in Fedora, you can install it via

.. code-block:: shell

  dnf install bpython


Ubuntu
------
The bpython package is included in the Ubuntu repositories starting at Ubuntu
9.10 Karmic Koala. You can install it with:

.. code-block:: shell

  apt-get install bpython

OpenSUSE
--------
openSUSE Tumbleweed users can install bpython from the official repositorios via

.. code-block:: shell

  zypper in python3-bpython

Up to date packages for other openSUSE releases can be found at

https://software.opensuse.org//download.html?project=devel%3Alanguages%3Apython&package=python-bpython

Please follow the instructions there to install bpython with `zypper`.

Solaris
-------
You can find bpython packages for Solaris on the sunfreeware website, kindly
provided for by Steven Christensen.

.. _documentation: https://cffi.readthedocs.org/en/release-0.8/#macos-x
.. _release page: /releases/

OpenBSD
-------
A bpython package is available in the OpenBSD repositories. You can install it with:

.. code-block:: shell

  pkg_add bpython
