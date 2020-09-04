..

:tocdepth: 1

.. sectnum::

.. note::

   **This technote is not yet published.**

   Fibers and copper deployed at La Serena


Introduction
=============

The purpose of this document is to provide information related to the installation, materials used, network point areas, and the number of fiber filaments used per floor. This documentation also reflects how the physical network of the base datacenter is built by putting an emphasis on the fact that the project is still undergoing construction and will undergo continuous changes in the near future. These changes include additional network points or removing those that are already in place. The materials used for this project were all selected based on their quality and technical properties so that the project can operate at maximum performance once in operations. 

Single-mode fiber was selected and installed due to its technical properties hence it provides an unlimited transmission limit. This fiber will only be used for the equipment that functions as a transmitter (TX). It is also noted that UTP S/FTP cables were also selected due to the cable properties and ability to work at 10GBASE-T speeds. All network points were installed with this type of cable, both the access points and telephony connection systems. In regard to end-user devices, UTP CAT6 was setup. In some occasions, multi-mode fiber cable connections will be set up and installed for any technical equipment that requires it.


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

The data center is currently composed of 2 rack rows A and B.

In row A there are  2 racks with Rubin equipment (Rack A1 / Rack A4).

Rack A1 is shared with Aura and Rubin, as for Rack A4 this is where our DWDM is located.

All of row B is designated for various Rubin's teams and projects, it also intended to use row C in the future if needed.

All optical terminals are centralized and located in Rack A1 inside the data center.

Rack A1 will be documented hence it focuses on the optical terminals for both the service terminals and the distribution terminals.

Rack A1 is also in charge of distributing all the fiber optic connections to the different optical terminals located at the "Recinto La Serena".

This activity was carried out based on the specifications delivered by the AURA IT group which also listed the various locations to set up connectivity.

Each individual optical terminal connects to one of the ends where another optical terminal is located, each one of these optical terminals correspond to a technical room.

In these optical terminals, you will find different types of optical fibers such as single mode OS2, multimode OM1 and OM3. Each one of these terminals have an LC UPC type connector.


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





The locations of the data points for the AP's were delivered by the network engineer in charge  who used an optimal signal monitoring program to determine this. 

Below is a diagram of the access points located at BDC.



Data Point / Access Point BDC
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/aps.PNG
    :name: aps
            :width: 700 px




PDU location
---------------


The following image provides information related to the PDUs installed in each rack in the Datacenter.

It is intented to setup all of the racks with 2 PDUs but this activity is currently still in progress. The image illustrated below shows the current status of this activity and amount of PDUs setup per rack. 

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
