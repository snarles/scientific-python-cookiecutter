===============================
{{ cookiecutter.project_name }}
===============================

.. image:: https://img.shields.io/travis/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}.svg
        :target: https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}

.. image:: https://img.shields.io/pypi/v/{{ cookiecutter.repo_name }}.svg
        :target: https://pypi.python.org/pypi/{{ cookiecutter.repo_name }}


{{ cookiecutter.project_short_description}}

* Free software: 3-clause BSD license
* Documentation: (COMING SOON!) `<https://{{ cookiecutter.github_username}}.github.io/{{ cookiecutter.repo_name }}>`_.
    - See the ``./docs`` directory for offline documentation.

Install/Upgrade
---------------

First, make sure you have Python version {{ cookiecutter.minimum_supported_python_version }} or greater.
For non-developers, install/upgrade the latest stable release.
Stable releases are added to the `releases <https://github.com/{{ cookiecutter.github_username}}/{{ cookiecutter.repo_name }}/releases>`_ page.

If there are no stable releases, or you know what you're doing, install the
latest version of the master branch by entering in a command terminal::

    $ pip3 install --upgrade https://github.com/{{ cookiecutter.github_username}}/{{ cookiecutter.repo_name }}/archive/master.tar.gz

Features
--------

* TODO

Contributing
------------

If you wish to contribute to {{ cookiecutter.repo_name }}, please see ``./CONTRIBUTING.rst``.

References
----------

This package's structure is a modified version of `NSLS-II's <https://github.com/NSLS-II/scientific-python-cookiecutter>`_
scientific python cookiecutter. See my forked version `here <https://github.com/snarles/scientific-python-cookiecutter>`_. 
