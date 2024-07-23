Release Notes Peregrine v3.1.4
==============================

============= =======================
Release date: 2024-07-22
Notes:        Peregrine 3.1.4 is a recommended install for all users.
============= =======================

UPDATES
-------

- Further error handling for CID/env files
- Log File review and clean up
- Zero Trust standalone dataset setup on service layer
- Zero Trust standalone dataset setup on presentation layer
- Updated to identify bad CIDs in configuration files
- Sorting added to Offline Queue
- Dropdown Finished Initialized for Offline Queue
- Sorting added to Cloud File
- Sorting added to RTR manager
- Sorting utility for Offline Queue, Cloud File and RTR manager
- Removed columns Offline Queue
- Search input added to Offline Queue
- Search input added to Cloud File
- Separated Device Explorer and Zero Trust datasets for separation of widget service
- Activation login Updated cancel on login to return user to multi config if wrong selection is made
- Added trim spaces for all sorting utilities
- Updated Datasets for Offline Queue, Cloud File and RTR manager to support standalone datasets
- Faster response when sending mis spelled CrowdStrike commands.

FIXES
-----

- Fixed sorting bug in Create and Modified Date in File Explorer Module
- Setconfig onload .env NFR client bug fix
- Fixed stats on login to run at same time as loading application
- Zero Trust reset widget fix
- Device explorer Fix for Empty set on refresh
- Check for empty set on authentication
- Dialog window rendering fix
- Fix to speed up RTR response when command is misspelled
- Cleaned up device files

CODE REVIEW
-----------

- Device Explorer
- Offline Queue
- Cloud File
- RTR manager
- Activation login

SHA256 CHECKSUMS
----------------

================================================================  ===========================
80fead5a0ba4db76d1c0db6a69507322a68454051ebce153ff10d7222c658bf0  Peregrine.exe (Windows)
61d434a75e950804d896c1c2ad48bc9ce8c9de46f9b07fb8384d88976f6ba896  peregrine-mac.tar (Mac x86)
================================================================  ===========================
