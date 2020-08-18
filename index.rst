..

:tocdepth: 1

.. sectnum::

.. note::

   **This technote is not yet published.**

   Fibers and copper deployed at La Serena


Introduction
=============

The following documentation, details the amount of materials and fiber filaments used throughout the setup and installation of the various network points at La Serena facility.

The materials selected were chosen based on their quality and technical properties, so the project can operate at its maximum performance.

Based on the equipment requirements, single mode fiber optic were installed in the building. However, if required, multimode fiber cables are also available for use when needed.


UTP S / FTP cables were utilized throughout the building, this was due to their technical properties when working at 10GBase-T speeds. All network points in the building were set up and installed with this type of cable for both the access points (AP) and telephony systems.


All end user device connections are based on UTP CAT6 cables. 




.. figure:: /_static/tabla.PNG
    :name: tabla
            :width: 700 px


La Serena facility was divided into the following areas:

- Data center
- Preparation room
- BDC offices
- Electrical room
- UPS room
- Cooling room

This documentation will primarily focus on the first 3 areas listed above.


Data center
===========

The data center is currently composed of 2 rack rows, these are known as row A and row B.

In row A there are  2 racks with Rubin equipment.

Rack A1 is shared with Aura and Rubin, as for Rack A4 this is where our DWDM is located.

All of row B is for our various Rubin's teams and projects, it also intended to use row C in the future if needed.

Rack A1 will be documented hence it focuses on the optical terminals for both the service terminals and the distribution terminals.


All optical terminals are centralized and located in Rack A1 inside the data center.

Rack A7 is in charge of distributing all the fiber optic connections to the different fiber optic points located at the "Recinto La Serena".

This activity was carried out based on the specifications delivered by the AURA IT group which also listed the various locations to set up connectivity.

Each individual optical terminal connects to one of the ends where another optical terminal is located, each one of these optical terminals correspond to a technical room.


In the optical terminals, you will find different types of optical fibers such as single mode OS2, multimode OM1 and OM3. Each one of these terminals have an LC UPC type connector.


Data Center Rack A1 Image
---------------------------

.. figure:: /_static/racka1.PNG
    :name: racka1
            :width: 700 px




Data Points at BDC
===================


The following section documents information related to our various data points.

The areas considered at the base data center were:

- 3 BDC Offices
- Preparation room
- Access Points


All data points start in rack A1 where the patch panel and the switch are located.

BDC rack A1 has the following characteristics in terms of materials and numbering of the various network points.

Rack A1:

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





The locations of the data points for the AP's were delivered by the network engineer who used an optimal signal monitoring program to determine this. 

Below is a diagram of the access points located at BDC.



Data Point / Access Point BDC
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/aps.PNG
    :name: aps
            :width: 700 px




PDU location
---------------


In the following image, you will information related the PDUs installed in each rack in the Datacenter.

At the moment we do not have 2 PDUs per rack and but we have plans to set this up in the future, as its necessary to have a main and a backup PDU system. 

Both Row A and B have 2 independent electrical circuits to each other.



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
