..
  Technote content.

  See https://developer.lsst.io/restructuredtext/style.html
  for a guide to reStructuredText writing.

  Do not put the title, authors or other metadata in this document;
  those are automatically added.

  Use the following syntax for sections:

  Sections
  ========

  and

  Subsections
  -----------

  and

  Subsubsections
  ^^^^^^^^^^^^^^

  To add images, add the image file (png, svg or jpeg preferred) to the
  _static/ directory. The reST syntax for adding the image is

  .. figure:: /_static/filename.ext
     :name: fig-label

     Caption text.

   Run: ``make html`` and ``open _build/html/index.html`` to preview your work.
   See the README at https://github.com/lsst-sqre/lsst-technote-bootstrap or
   this repo's README for more info.

   Feel free to delete this instructional comment.

:tocdepth: 1

.. Please do not modify tocdepth; will be fixed when a new Sphinx theme is shipped.

.. sectnum::

.. TODO: Delete the note below before merging new content to the master branch.

.. note::

   **This technote is not yet published.**

   Fibers and copper deployed at La Serena

.. Add content here.

Introduction
=============


In the following document and information to be provided, it is related to the installation, material, and location of network points, such as fiber optics.
This document will present information on the location of the data points, the quantity, and also the location and quantity of fiber filaments per location.
This document reflects how the Physical Calibration Hill and AuxTel Network are built and which project is still under construction may undergo future changes such as adding connection points and deleting.
The materials used were selected for their quality and properties so that the project in its operation works at its maximum performance.
The Singlemode fiber optic point cable was installed since in practice there is no transmission limit, only the equipment that transmits.
The UTP S / FTP cable was selected for its properties to work at 10G / base T and all network points will be installed with this type of cable, for both AP and telephone connections.
As for everything that is the user's cable is with UTP CAT6 cable
On some occasions, the multimode cable will be installed only when the equipment needs it.






















.. Do not include the document title (it's automatically added from metadata.yaml).

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
