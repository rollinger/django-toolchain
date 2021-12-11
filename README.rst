.. image:: https://img.shields.io/pypi/v/skeleton.svg
   :target: `PyPI link`_

.. image:: https://img.shields.io/pypi/pyversions/skeleton.svg
   :target: `PyPI link`_

.. _PyPI link: https://pypi.org/project/skeleton

.. image:: https://github.com/jaraco/skeleton/workflows/tests/badge.svg
   :target: https://github.com/jaraco/skeleton/actions?query=workflow%3A%22tests%22
   :alt: tests

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/psf/black
   :alt: Code style: Black

.. .. image:: https://readthedocs.org/projects/skeleton/badge/?version=latest
..    :target: https://skeleton.readthedocs.io/en/latest/?badge=latest

.. image:: https://img.shields.io/badge/skeleton-2021-informational
   :target: https://blog.jaraco.com/skeleton

Django Toolchain is a collection of management commands for the Django Framework.


Getting Started
===============

After installation in your project run:
    
    $ python manage.py <command>

Requirements
============

Django Extensions requires Django 3.8 or later.


Getting It
==========

You can get Django Toolchain by using pip::

    $ pip install django-toolchain

If you want to install it from source, grab the git repository from GitHub and run setup.py::

    $ git clone git://github.com/rollinger/django-toolchain
    $ cd django-toolchain
    $ python setup.py install


Installing It
=============

To enable `django_toolchain` in your project you need to add it to `INSTALLED_APPS` in your projects
`settings.py` file::

    INSTALLED_APPS = (
        ...
        'Django-Toolchain',
        ...
    )


Using It
========

Toolchains change your project in sometimes unpredictable ways! 
A git branch before using any of the toolchain commands is highly recommended.

Manage App Structure:

    $ python manage.py tool_structure [check|run] --Package|Class|method|function

Manage docstrings:

    $ python manage.py tool_docstrings [check|run]

Manage translatables:

    $ python manage.py tool_translatables [check|run]

Manage pytests:

    $ python manage.py tool_pytests [check|run]


Getting Involved
================

Open Source projects can always use more help. Fixing a problem, documenting a feature, adding
translation in your language. If you have some time to spare and like to help us, here are the places to do so:

- GitHub: git://github.com/rollinger/django-toolchain


Documentation
=============

You can view documentation in the docs/ folder


Support
=======

Django Toolchain is free and always will be. It is developed and maintained by developers in an Open Source manner.
Any support is welcome. You could help by writing documentation, pull-requests, report issues and/or translations.

Please remember that nobody is paid directly to develop or maintain Django Toolchain so we do have to divide our time
between putting food on the table, family, this project and the rest of life :-)
