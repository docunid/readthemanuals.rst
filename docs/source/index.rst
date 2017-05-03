.. readthemanuals documentation master file, created by
   sphinx-quickstart on Wed Sep 28 15:20:48 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to readthemanuals's documentation!
==========================================

Contents:

.. toctree::
   :maxdepth: 2



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Definition lists: 

what 
  Definition lists associate a term with 
  a definition. 

how 
  The term is a one-line phrase, and the 
  definition is one or more paragraphs or 
  body elements, indented relative to the 
  term. Blank lines are not allowed 
  between term and definition.

Directives
**********

.. code-block:: html
    :linenos:

    <h1>code block example</h1>

.. hlist::
    :columns: 3

    * first item
    * second item
    * 3d item
    * 4th item
    * 5th item

.. sidebar:: Sidebar Title
    :subtitle: Optional Sidebar Subtitle

    Subsequent indented lines comprise
    the body of the sidebar, and are
    interpreted as body elements.

.. note::  This is a **note** box.

.. todo::  This is a **todo** box.

Why there is no todo

.. topic:: Your Topic Title

    Subsequent indented lines comprise
    the body of the topic, and are
    interpreted as body elements.

What happens when writing here
