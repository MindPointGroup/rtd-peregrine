Release Notes Peregrine™ v3.1.0
==============================

============= =======================
Release date: 2024-04-19
Notes:        Peregrine 3.1.0 is a recommended install for all users. 
============= =======================

OVERVIEW
--------

- Added in functionality to filter device by Last Seen and Groups on load and in host explorer module.
- Increased functionality with submit and clear to work with filters in host explorer.
- Device count and time to load host explorer is now being sent to license server.
- Added service level functionality for pagination
- Added consistency for user experience across modules
- Updated CID Management module to show only the names for the CID versus the CID number
- Updated queue offline checkbox to be consistent across application
- Updated Zero Trust error handling

DETAILS
-------

UPDATES
-------

- Filter by Last Seen
- Filter by Group host
- Refactored Device Host explorer into 2 files Utilities and container
- Removed Search forms UI container extra padding
- CrowdStrike Detection UI consistency
- Kill Process by Name UI consistency
- Updated Submit to handle Filter submission
- Updated Clear to clear Filter submission
- On Login maintain Filter selection
- Error handler updated ZeroTrust
- Device information updated service layer

FIXES
-----

- Add New CID selection was not being maintained
- MCID Updated Data set removed all ids only display names
- Queue Offline fixes for Task Manager and Processes
- Queue Offline fixes for Kill Process by name
- Zero Trust Queue Offline
- Filter by Name adjustments when combined with input

CODE REVIEW
-----------

- Kill Process by name
- Member CID
- Offline Queue
- Remote Explorer Table
- Task Manager
- Configuration Manager
- Extended Details

SHA256 CHECKSUMS
----------------

================================================================  ===========================
54ab26997bfdfc5eaf7fd5da0f71c03721c7820bb6e952b957384efcecec67da  Peregrine.exe (Windows)
5548229403bca74e0f50dc05b38e5a4cacb769bb2f810dc97df71177cdb5fb7e  peregrine-mac.tar (Mac x86)
================================================================  ===========================
