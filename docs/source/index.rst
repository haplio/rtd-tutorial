Welcome to RTD Tutorial documentation!
===================================

**RTD Tutorial** (/lu'make/) is a test documentation site for checking how docs-as-code tools work.
It is currently located at the URL `RTD Tutorial Docs <https://haplio-rtd-tutorial.readthedocs.io/>`_

*This is how we do italics*

This is how we link to named pages in our repo like: :doc:`next-begin`

This is how we link to named headings anywhere in our doc: :ref:`subheading_1`

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

.. note::
   Creating a test note here

Contents
--------

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Original Tree
   :name: sec-original

   usage
   api
   moving-on

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Next Tree
   :name: sec-next

   next-begin
