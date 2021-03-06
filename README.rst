|logo|

Tornado-based boilerplate for API projects
--------------------------------------------

.. image:: https://travis-ci.org/gakhov/api.boilerplate.svg?branch=master
   :target: https://travis-ci.org/gakhov/api.boilerplate

.. image:: https://coveralls.io/repos/github/gakhov/api.boilerplate/badge.svg?branch=master
   :target: https://coveralls.io/github/gakhov/api.boilerplate?branch=master


How to start
-------------

First, you need to clone or fork our API boilerplate. If you choose clone, go to your machine and run

.. code-block:: bash

    $ git clone git@github.com:gakhov/api.boilerplate.git myfolder
    $ cd myfolder

Afterwards you need to add your remote to the git repository to be able commit your changes:

.. code-block:: bash

    $ git remote rename origin boilerplate
    $ git remote add origin https://github.com/{user}/{your_repo}.git


Documentation
-------------

* `HEAD <http://apiboilerplate.readthedocs.io/en/latest/>`_


How to run
-------------

.. code-block:: bash

    $ bin/start_server -h
    usage: start_server [-h] [--name NAME] [--port PORT] [--settings SETTINGS]
    $ bin/start_server --name server --port 5570


.. |logo| image:: https://raw.githubusercontent.com/gakhov/api.boilerplate/master/api/docs/_static/logo.png
