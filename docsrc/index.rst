.. address-entity-extraction documentation master file.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

address-entity-extraction Documentation
=============================================================================================================

This documentation is generated from the template defined in ``./docsrc/source/index.rst``. This location and
file is the place to start creating documentation for your project.

reStructured Text
-----------------

Since not everybody knows the reStructured Text syntax cold, it does help to have a good reference or two.

* `reStructured Text Cheat Sheet`_

NBSphinx
--------

Since frequently Jupyter Notebooks are valuable documentation in themselves, using `NBSphinx`_ you can include
them directly in the documentation. Just ensure you start the notebook with a markdown cell using a level one
header (``# Level One Title``).

Contents
========

.. toctree::
    :maxdepth: 2

    Notebook Template <notebooks/notebook-template>

address_entity_extraction
================================

Example using the `Sphinx Autodoc`_ extension to document the automatically included support library for this
project located in ``./src/address_entity_extraction``.

.. automodule:: address_entity_extraction
    :members:

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. _reStructured Text Cheat Sheet: https://thomas-cokelaer.info/tutorials/sphinx/rest_syntax.html
.. _NBSphinx: https://nbsphinx.readthedocs.io/en/0.8.8/
.. _Sphinx Autodoc: https://www.sphinx-doc.org/en/master/usage/extensions/autodoc.html