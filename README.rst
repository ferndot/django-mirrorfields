=============================
Django Mirror Fields
=============================

.. image:: https://badge.fury.io/py/django-mirrorfields.svg
    :target: https://badge.fury.io/py/django-mirrorfields

.. image:: https://travis-ci.org/joshua-s/django-mirrorfields.svg?branch=master
    :target: https://travis-ci.org/joshua-s/django-mirrorfields

.. image:: https://codecov.io/gh/joshua-s/django-mirrorfields/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/joshua-s/django-mirrorfields

The pane-less way to denormalize data

Documentation
-------------

The full documentation is at https://django-mirrorfields.readthedocs.io.

Quickstart
----------

Install Django Mirror Fields::

    pip install django-mirrorfields

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'django_mirrorfields.apps.DjangoMirrorfieldsConfig',
        ...
    )

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox


Development commands
---------------------

::

    pip install -r requirements_dev.txt
    invoke -l


Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
