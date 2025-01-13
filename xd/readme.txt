cbmSD-xd - SD Card Drive for Commodore Computers with IEEE
==========================================================

**NEW** Webpage: http://cbmsteve.ca/cbmsd/index.html

The goal of this project is to create a free open-source
disk drive solution that is easy to build using all
thru-hole parts plus the use of a common inexpensive SD
card module.

This device is based on the petSD+ v2.4 from Nils Eilers.

This is a variant of cbmSD-mini. The "XD" stands for
eXternal Drive (or eXperimental Device as I am not sure
what the ultimate form this might be).

This version comes in two parts:

1) IEEE pass-thru and "cbmSD" connector.
2) cbmSD-xd board

The pass-thru plugs into the back of the PET/CBM and connects
to power (via cassette port or power adapter). The "XD"
connector combines the power and IEEE signals into one
proprietary pinout for convenient connection to the cbmSD-xd
board using a simple 20-pin ribbon cable. Note: That the IEEE
standard is a 24-pin connector. The GROUND pins have been
consolidated and 5V pins have been added.

You will need a simple cassette port power plug or you can
power it with a standard 5V adapter with barrel jack.

Features
--------

- Requires cbmSD-pass board (there are 2 variations)
- Proprietary 20-pin IEEE/Power connector
- Power, Busy and Error lights
- SD module is mounted directly to pcb so it does not mount
  overtop any components
- Reset switch.
- Mounting holes for future 3D case.

Status
------

 V1.0: First release. Verified working as intended.

Steve
2025-01-13