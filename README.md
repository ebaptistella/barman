barman
======
Barman (Backup and Recovery Manager) is an open-source administration tool for disaster recovery of PostgreSQL servers written in Python.

Source Code
----
Available in: https://sourceforge.net/u/euridesb/pgbarman/


Difference between the original and my patches
----
- Support for OpenSuse (tested on version 12.2)
- Changed restore directory. Added a directory "data" after the default directory "pgdata" (pgdata/data/* possibly just a need on my part)
