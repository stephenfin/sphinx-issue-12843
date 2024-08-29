==================================
Reproducer for Sphinx Issue #12843
==================================

See `github.com/sphinx-doc/sphinx#12843 <https://github.com/sphinx-doc/sphinx/issues/12843>`__ for more information.

To run:

.. code-block:: shell

    virtualenv .venv
    source .venv
    pip install sphinx
    make -C doc html
