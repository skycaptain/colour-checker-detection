Colour - Checker Detection
==========================

..  image:: https://raw.githubusercontent.com/colour-science/colour-checker-detection/master/docs/_static/ColourCheckerDetection_001.png

A `Python <https://www.python.org/>`_ package implementing various colour
checker detection algorithms and related utilities.

It is open source and freely available under the
`New BSD License <http://opensource.org/licenses/BSD-3-Clause>`_ terms.

Features
--------

The following colour checker detection algorithms are implemented:

-   Segmentation

Installation
------------

Because of their size, the resources dependencies needed to run the various
examples and unit tests are not provided within the Pypi package. They are
separately available as
`Git Submodules <https://git-scm.com/book/en/v2/Git-Tools-Submodules>`_
when cloning the
`repository <https://github.com/colour-science/colour-checker-detection>`_.

Primary Dependencies
^^^^^^^^^^^^^^^^^^^^

**Colour - Checker Detection** requires various dependencies in order to run:

-  `Python 2.7 <https://www.python.org/download/releases/>`_ or
   `Python 3.5 <https://www.python.org/download/releases/>`_
-  `Colour Science <https://www.colour-science.org>`_
-  `NumPy <http://www.numpy.org/>`_
-  `OpenImageIO <https://github.com/OpenImageIO/oiio>`_

Pypi
^^^^

Once the dependencies satisfied, **Colour - Checker Detection** can be installed from
the `Python Package Index <http://pypi.python.org/pypi/colour-checker-detection>`_ by
issuing this command in a shell::

	pip install colour-checker-detection

The tests suite dependencies are installed as follows::

    pip install 'colour-checker-detection[tests]'

The documentation building dependencies are installed as follows::

    pip install 'colour-checker-detection[docs]'

The overall development dependencies are installed as follows::

    pip install 'colour-checker-detection[development]'

Usage
-----

API
^^^

The main reference for
`Colour - Demosaicing <https://github.com/colour-science/colour-checker-detection>`_
is the manual:

.. toctree::
    :maxdepth: 4

    manual

Examples
^^^^^^^^

Various usage examples are available from the
`examples directory <https://github.com/colour-science/colour-checker-detection/tree/master/colour_checker_detection/examples>`_.

Contributing
------------

If you would like to contribute to `Colour - Checker Detection <https://github.com/colour-science/colour-checker-detection>`_,
please refer to the following `Contributing <https://www.colour-science.org/contributing/>`_
guide for `Colour <https://github.com/colour-science/colour>`_.

Bibliography
------------

The bibliography is available in the repository in
`BibTeX <https://github.com/colour-science/colour-checker-detection/blob/develop/BIBLIOGRAPHY.bib>`_
format.

About
-----

| **Colour - Checker Detection** by Colour Developers
| Copyright © 2015-2018 – Colour Developers – `colour-science@googlegroups.com <colour-science@googlegroups.com>`_
| This software is released under terms of New BSD License: http://opensource.org/licenses/BSD-3-Clause
| `http://github.com/colour-science/colour-checker-detection <http://github.com/colour-science/colour-checker-detection>`_
