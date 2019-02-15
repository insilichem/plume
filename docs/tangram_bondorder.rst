=================
Tangram BondOrder
=================

.. image:: https://img.shields.io/github/release/insilichem/tangram_bondorder.svg
    :target: https://github.com/insilichem/tangram_bondorder

.. image:: https://img.shields.io/github/issues/insilichem/tangram_bondorder.svg
    :target: https://github.com/insilichem/tangram_bondorder/issues

Automatic bond order perception for UCSF Chimera [WIP]

Features
========

While UCSF Chimera does have some kind of bond order perception that supports its internal atom typing engine (see `[Chimera-users] bond order`_), this information is not available to the user (not even in the Python API). This extension tries to fill the gap by providing a graphic interface to perceive bond order with external programs and/or set them manually.

Usage
=====

[WIP]

This extension is still under development. Documentation will be ready once basic functionality is achieved.

Requirements
============

- ``libtangram``
- ``rdkit``
- ``ambermini``

::

    conda install -c insilichem -c rdkit -c omnia tangram_bondorder

.. _[Chimera-users] bond order: http://www.cgl.ucsf.edu/pipermail/chimera-users/2009-October/004403.html