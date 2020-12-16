template_demo
===========================

|build_status| |coverage| |pypi_version| |license|

test

============== ==============================================================
PyPI           ``pip install template_demo``
Source code    https://github.com/dls-controls/template_demo
Documentation  https://dls-controls.github.io/template_demo
============== ==============================================================

test

.. code:: python

    from template_demo import HelloClass

    hello = HelloClass("me")
    print(hello.format_greeting())

Or if it is a commandline tool then you might put some example commands here::

    template_demo person --times=2


.. |build_status| image:: https://github.com/dls-controls/template_demo/workflows/Python%20CI/badge.svg?branch=master
    :target: https://github.com/dls-controls/template_demo/actions?query=workflow%3A%22Python+CI%22
    :alt: Build Status

.. |coverage| image:: https://dls-controls.github.io/template_demo/coverage.svg
    :target: https://github.com/dls-controls/template_demo/actions?query=workflow%3A%22Python+CI%22
    :alt: Test Coverage

.. |pypi_version| image:: https://img.shields.io/pypi/v/template_demo.svg
    :target: https://pypi.org/project/template_demo
    :alt: Latest PyPI version

.. |license| image:: https://img.shields.io/badge/License-Apache%202.0-blue.svg
    :target: https://opensource.org/licenses/Apache-2.0
    :alt: Apache License

..
    Anything below this line is used when viewing README.rst and will be replaced
    when included in index.rst
