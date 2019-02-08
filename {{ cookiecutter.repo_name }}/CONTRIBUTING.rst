============
Contributing
============

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

You can contribute in many ways:

Types of Contributions
----------------------

Report Bugs
~~~~~~~~~~~

Report bugs at `<https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}/issues>`_.

If you are reporting a bug, please include:

* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

Fix Bugs
~~~~~~~~

Look through the GitHub issues for bugs. Anything tagged with "bug"
is open to whoever wants to implement it.

Implement Features
~~~~~~~~~~~~~~~~~~

Look through the GitHub issues for features. Anything tagged with "feature"
is open to whoever wants to implement it.

Write Documentation
~~~~~~~~~~~~~~~~~~~

{{ cookiecutter.project_name }} could always use more documentation, whether
as part of the official {{ cookiecutter.project_name }} docs, in docstrings,
or even on the web in blog posts, articles, and such.

Submit Feedback
~~~~~~~~~~~~~~~

The best way to send feedback is to file an issue at `<https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}/issues>`_.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Remember that this is a volunteer-driven project, and that contributions
  are welcome :)

Get Started!
------------

Ready to contribute? Here's how to set up `{{ cookiecutter.package_dist_name }}` for local development.

1. Fork the `{{ cookiecutter.repo_name }}` repo on GitHub (see `<https://guides.github.com/activities/forking/>`_).

2. Clone the repository locally::

    $ git clone https://github.com/your-github-username-here/{{ cookiecutter.repo_name }}.git

3. Install your local copy into a virtualenv. Assuming you have `Anaconda <https://www.anaconda.com/>`_ installed, this is how you set up your fork for local development::

    $ conda create -n {{ cookiecutter.repo_name }} python={{ cookiecutter.minimum_supported_python_version }}  #Create a virtual environment (only do this once).
    $ source activate {{ cookiecutter.repo_name }}  #Enter the virtual environment (do this every time).
    $ pip3 install -e .  #Install the project for development.
    $ pip3 install --upgrade -r requirements-dev.txt  #Install development requirements.

4. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature

   Now you can make your changes locally. Make sure to make a new branch for each feature. Do **not** make changes directly to the master branch.

5. When you're done making changes, check that your changes pass the flake8 syntax checker and all unit tests pass::

    $ flake8
    $ pytest

6. Commit your changes and push your branch to GitHub (read `<https://chris.beams.io/posts/git-commit/>`_)::

    $ git add .
    $ git commit -m "Describe changes with 50 characters or less"
    $ git push origin name-of-your-bugfix-or-feature

7. Submit a pull request through the GitHub website.

Pull Request Guidelines
-----------------------

Before you submit a pull request, check that it meets these guidelines:

1. The pull request should include tests.
2. If the pull request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in ``./README.rst``.
3. The pull request should work for Python versions as specified in the ``./.travis.yaml`` file. Check
   `<https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}/pull_requests>`_
   and make sure that the tests pass for all supported Python versions.

References
----------

The text in this file is modified from `NSLS-II <https://github.com/NSLS-II/scientific-python-cookiecutter>`_.
It is difficult to trace the origins of the text because so many projects have similar contributing files.
If anyone knows the original author, please add an issue to the GitHub page, so proper credit can be given.
