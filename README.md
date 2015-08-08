=========================
Cookiecutter Pytest Plugin
=========================

.. image:: https://badges.gitter.im/Join%20Chat.svg
    :target: https://gitter.im/pytest-dev/cookiecutter-pytest-plugin?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
    :alt: Join Chat on Gitter.im

.. image:: https://travis-ci.org/pytest-dev/cookiecutter-pytest-plugin.svg?branch=master
    :target: https://travis-ci.org/pytest-dev/cookiecutter-pytest-plugin
    :alt: See Build Status on Travis CI

.. image:: https://readthedocs.org/projects/cookiecutter-pytest-plugin/badge/?version=latest
        :target: https://readthedocs.org/projects/cookiecutter-pytest-plugin/?badge=latest
        :alt: Documentation Status

Minimal `Cookiecutter`_ template for authoring  `pytest`_ plugins that help you to write better programs.

Features
--------

* Installable `PyPI`_ package featuring a ``setup.py``.
* Test suite running `tox`_ and `pytest`_ that makes sure your plugin is working as expected
* Comprehensive ``README.rst`` file that contains useful information about your plugin


Usage
-----

Generate a Pytest plugin project::

    cookiecutter https://github.com/pytest-dev/pytest-foo


Requirements to Submit Your Plugin
----------------------------------

* PyPI presence with a setup.py that contains a license, pytest- prefixed, version number, authors, short and long description.
* a tox.ini for running tests using tox.
* a README describing how to use the plugin and on which platforms it runs.
* a LICENSE file or equivalent containing the licensing information, with matching info in setup.py.
* an issue tracker unless you rather want to use the core pytest issue tracker.

Please see the official guidelines at `Submit a Plugin`_.


Resources
---------

Please consult the `pytest`_ docs for more information on hooks at `Pytest Hook Reference`_.


License
-------

Distributed under the terms of the `MIT license`_, Cookiecutter Pytest Plugin is free and open source software


Issues
------

This template has been tested on Mac OS X Yosemite.

If you encounter any problems, please `file an issue`_ along with a detailed description.

.. _`Cookiecutter`: https://github.com/audreyr/cookiecutter
.. _`MIT License`: http://opensource.org/licenses/MIT
.. _`PyPI`: https://pypi.python.org/pypi
.. _`Pytest Hook Reference`: https://pytest.org/latest/plugins.html#well-specified-hooks
.. _`Submit a Plugin`: https://pytest.org/latest/contributing.html#submit-a-plugin-co-develop-pytest
.. _`file an issue`: https://github.com/pytest-dev/cookiecutter-pytest-plugin/issues
.. _`pytest`: https://github.com/pytest-dev/pytest
.. _`tox`: https://tox.readthedocs.org/en/latest/