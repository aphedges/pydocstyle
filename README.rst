pydocstyle - docstring style checker
====================================


.. image:: https://github.com/PyCQA/pydocstyle/workflows/Run%20tests/badge.svg
    :target: https://github.com/PyCQA/pydocstyle/actions?query=workflow%3A%22Run+tests%22+branch%3Amaster

.. image:: https://readthedocs.org/projects/pydocstyle/badge/?version=latest
    :target: https://readthedocs.org/projects/pydocstyle/?badge=latest
    :alt: Documentation Status

.. image:: https://img.shields.io/pypi/pyversions/pydocstyle.svg
    :target: https://pypi.org/project/pydocstyle

.. image:: https://pepy.tech/badge/pydocstyle
    :target: https://pepy.tech/project/pydocstyle

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/psf/black

.. image:: https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336
    :target: https://pycqa.github.io/isort/

.. image:: https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod
    :target: https://gitpod.io/#https://github.com/PyCQA/pydocstyle
    :alt: Gitpod ready-to-code

**pydocstyle** is a static analysis tool for checking compliance with Python
docstring conventions.

**pydocstyle** supports most of
`PEP 257 <http://www.python.org/dev/peps/pep-0257/>`_ out of the box, but it
should not be considered a reference implementation.

**pydocstyle** supports Python 3.6+.


Quick Start
-----------

Install
^^^^^^^

.. code::

    pip install pydocstyle


Run
^^^

.. code::

    $ pydocstyle test.py
    test.py:18 in private nested class `meta`:
            D101: Docstring missing
    test.py:27 in public function `get_user`:
        D300: Use """triple double quotes""" (found '''-quotes)
    test:75 in public function `init_database`:
        D201: No blank lines allowed before function docstring (found 1)
    ...

Develop
^^^^^^^

You can use Gitpod to run pre-configured dev envrionment in the cloud right from your browser -

.. image:: https://gitpod.io/button/open-in-gitpod.svg
    :target: https://gitpod.io/#https://github.com/PyCQA/pydocstyle
    :alt: Open in Gitpod
    
Before submitting a PR make sure that you run `make all`.

Links
-----

* `Read the full documentation here <http://pydocstyle.org/en/stable/>`_.

* `Fork pydocstyle on GitHub <http://github.com/PyCQA/pydocstyle>`_.

* `PyPI project page <https://pypi.python.org/pypi/pydocstyle>`_.
