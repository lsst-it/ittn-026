..

:tocdepth: 1

.. sectnum::

.. note::

   **This technote is not yet published.**

   Fibers and copper deployed at La Serena


Introduction
=============


The following document details the installation, material, quantity of fiber filaments, and location of network points at La Serena facilities.

The materials selected were chosen for their quality and properties so the project can operate at its maximum performance.

The Single mode fiber optics were installed due to equipment requirements, however, if the equipment needs it, multimode cable is also available.

The UTP S / FTP cable are utilized for its properties to work at 10G / base T and all network points are installed with this type of cable, for both AP and telephone connections.

User's connections are UTP CAT6 cable




.. figure:: /_static/tabla.PNG
    :name: tabla
            :width: 700 px


La Serena facilities has been divided in the following areas:

- Datacenter
- Preparation room
- BDC offices
- Electrical room
- UPS room
- Cooling room

This document will focus on the first 3 areas


Data center
===========

On the following document, I will provide an explanation as to what we have inside the datacenter.

We currently have 2 rack rows known as row A and row B.

In row A we have 2 racks with Rubin equipment.

Rack A1 is shared with Aura and Rubin and Rack A4 we have our DWDM.

All row B we have our Rubin teams and in the future, it is intended to have row C.

In this section, I will document the Rack A1 since it concentrates on the optical terminals both the service terminals and the distribution terminals.

The concentration of optical terminals is located in Rack A1 inside the data center.

In rack A7 it distributes fiber optic connections for the different fiber optic points in the "recinto La Serena"

This work was installed with the specifications that Aura IT group delivered and also the places to connect.

Each optical terminal connects to the other end with another optical terminal in its corresponding technical rooms.

In the optical terminals, there are different types of optical fiber such as Singlemode OS2, multimode OM1, OM3
The connectors on the optical terminals correspond to the LC UPC type.



Data Center Rack A1 Image
---------------------------

.. figure:: /_static/racka1.PNG
    :name: racka1
            :width: 700 px




Data Points at BDC
===================


In this session. I will document the information from the data points.
The points that were considered in the BDC are:


- 3 BDC Offices
- Preparation room
- Access Point


All data points start in rack A1 where a patch panel and a switch are located.

In the BDC rack A1, it consists of the following characteristics in terms of materials and numbering of network points.


- 24 Network points in total (in the patch panels}
- 1 Patch panel
- 1 48-port switch
- 2 PDUs (primary and backup)
- 1 48U Rack
- 4 Access Points



Data Points BDC Image
--------------------------------

.. figure:: /_static/datacenter.PNG
    :name: datacenter
            :width: 700 px





The data points for the access points were delivered by the network engineer and at the same time from an optimal signal monitoring program.

I will also show the diagram of the Access Point.



Data Point Access Point BDC
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/aps.PNG
    :name: aps
            :width: 700 px




PDU location
---------------


In the following image, I will include information of the PDUs installed by each rack in the Datacenter

At the moment we do not have 2 PDUs per rack and we have plans to complete all racks with 2 PDUs, as they are necessary to have main and backup.

Rows A and B have 2 independent electrical circuits to each other.



PDUs Image
^^^^^^^^^^^^

.. figure:: /_static/pdu.PNG
    :name: pdu
            :width: 700 px















.. Do not include the document title (it's automatically added from metadata.yaml).

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
