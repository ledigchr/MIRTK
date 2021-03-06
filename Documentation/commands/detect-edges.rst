:orphan:

.. Auto-generated by mirtk-help-rst from "mirtk detect-edges -h" output

detect-edges
============

.. program:: detect-edges


Synopsis
--------

::

    mirtk detect-edges <input> <output> [options]


Description
-----------

.. include:: _descriptions/detect-edges.rst



Arguments
---------

.. option:: input

   Input greyscale image.

.. option:: output

   Output edge map.


Command options
---------------

.. option:: -sigma <float>

   Standard deviation of Gaussian blurring filter. (default: 0)

.. option:: -central

   Use central differences. (default)

.. option:: -sobel

   Use Sobel operator.

.. option:: -prewitt

   Use Prewitt operator.

.. option:: -laplace

   Use Laplace operator.

.. option:: -differential

   Use differential edge detection.


Standard options
----------------

.. option:: -v, -verbose [n]

   Increase/Set verbosity of output messages. (default: 0)

.. option:: -debug [level]

   Increase/Set debug level for output of intermediate results. (default: 0)

.. option:: -version [major.minor]

   Print version and exit or set version to emulate.

.. option:: -revision

   Print revision (or version) number only and exit.

.. option:: -h, -help

   Print help and exit.
