Livre Python
============

.. image:: https://travis-ci.org/HE-Arc/livre-python.svg?branch=master
    :target: https://travis-ci.org/HE-Arc/livre-python


Compilation
-----------

.. code-block:: bash

    $ pip install -r requirements.txt
    $ sphinx-build -Wn -b html source build/html
    $ sphinx-build -Wn -b latex source build/latex
    $ sphinx-build -Wn -b epub source build/epub
