Prerequisites
=============

Install cURL
------------

Download the `cURL <https://curl.haxx.se/download.html>`__ tool if not
already installed.

Docker and Docker Compose
-------------------------

You will need the following installed on the platform on which you will be
operating, or developing on (or for), Hyperledger Fabric:

  - MacOSX, *nix, or Windows 10: `Docker <https://www.docker.com/products/overview>`__
    v1.12 or greater is required.
  - Older versions of Windows: `Docker
    Toolbox <https://docs.docker.com/toolbox/toolbox_install_windows/>`__ -
    again, Docker version v1.12 or greater is required.

You can check the version of Docker you have installed with the following
command from a terminal prompt:

.. code:: bash

  docker --version

.. note:: Installing Docker for Mac or Windows, or Docker Toolbox will also
          install Docker Compose. If you already had Docker installed, you
          should check that you have Docker Compose version 1.8 or greater
          installed. If not, we recommend that you install a more recent
          version of Docker.

You can check the version of Docker Compose you have installed with the
following command from a terminal prompt:

.. code:: bash

  docker-compose --version

Go Programming Language
-----------------------

Hyperledger Fabric uses the Go programming language 1.7.x for many of its
components.

.. note: Go version 1.8.x will yield test failures

  - `Go <https://golang.org/>`__ - version 1.7.x

Node.js Runtime and NPM
-----------------------

If you will be developing applications for Hyperledger Fabric leveraging the
Fabric SDK for Node.js, you will need to have version 6.9.x of Node.js
installed.

.. note:: Node.js version 7.x is not supported at this time.

  - `Node.js <https://nodejs.org/en/download/>`__ - version 6.9.x or greater

.. note:: Installing Node.js will also install NPM, however it is recommended
          that you update the default version of NPM installed. You can upgrade
          the ``npm`` tool with the following command:

.. code:: bash

  npm install npm@latest -g

Windows extras
--------------

If you are developing on Windows, you may also need the following which
provides a better alternative to the built-in Windows tools:

  - `Git Bash <https://git-scm.com/downloads>`__
  - `make for MinGW <http://sourceforge.net/projects/mingw/files/MinGW/Extension/make/make-3.82.90-cvs/make-3.82.90-2-mingw32-cvs-20120902-bin.tar.lzma>`__ to be added to Git Bash

.. Licensed under Creative Commons Attribution 4.0 International License
