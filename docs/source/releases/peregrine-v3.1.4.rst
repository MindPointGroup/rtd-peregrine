Release Notes Peregrine v3.1.3
==============================

============= =======================
Release date: 2024-06-14
Notes:        Peregrine 3.1.3 is a recommended install for all users.
============= =======================

UPDATES
-------

- Zero Trust enhancements:
- Pagination, UI enhancements, and optional data call on startup
- Zero Trust now maintains state throughout click-through of application
- Further error handling for CID/env files
- Updated batch functionality for Test CrowdStrike detection
- Created code to identify bad CID’s in configuration files
- Made zero trust optional when providing host information to the user as well as refreshing the host list
- Update offline Queue to show completed result in the record set.
- Enhance load speed of application by modifying how stats are sent to the license server.
- Separated Device Explorer and Zero Trust datasets for separation of widget services
- Built customizable Button with Hover, tapped, and selected states.
- Updated sort buttons with enhanced button theme Device Explorer
- Updated sort buttons with enhanced button theme Zero Trust
- Updated sort buttons with enhanced button theme Task Manger
- Updated sort buttons with enhanced button theme File Explorer

FIXES
-----

- Fixed sorting bug in Create and Modified Date in File Explorer Module
- Fixed NRF issue with app crashing
- Fixed Zero Trust Sort issues
- Fixed Zero Trust Pagination issues
- Fixed Device Explorer Sort issues
- Fixed Device Explorer Pagination issues
- Fixed Zero Trust maintain selection state
- Fixed Zero Trust Clear no resetting pagination
- Fixed Zero Trust not refreshing Table data when switching to new configuration file.

CODE REVIEW
-----------

- Zero Trust
- Extended Button fileA

SHA256 CHECKSUMS
----------------

================================================================  ===========================
93e0d793b18ca686d0d905c2c71208cff69b01009c5893a50bc123828201f25c  Peregrine.exe (Windows)
01154de65dcae5274d9200333cdccc7ae562389e94b8eb5b0763c9b56e172e79  peregrine-mac.tar (Mac x86)
================================================================  ===========================
