Release Notes Peregrine v3.1.2
==============================

============= =======================
Release date: 2024-05-17
Notes:        Peregrine 3.1.2 is a recommended install for all users.
              *Peregrine 3.1.1* was not released. 
============= =======================

OVERVIEW
--------

- Added pagination to host explorer table as well as updated clear and submit to handle pagination
- Updated Cloud File and Queue Offline to load on module selection as well as adding progress bar
- Enhanced user experience by identifying bad .env files when application loads as well as confirmation box when deleting .env files and saved MCID’s in configuration management.
- Refresh in host explorer has been updated to use filtered results.
- Enhanced user experience with the ability to hit enter to perform action in modules versus having to click the submit button with mouse.
- Updated Queue Offline query to use command creation date vs session creation date.

DETAILS
-------

UPDATES
-------
- Pagination Setup Presentation Layer
- Pagination Setup Service layer
- Refactored Device Host explorer into 2 files Utilities and container
- Clear Operation update to handle pagination
- Submit operation to handle pagination
- Filtering operation to handle pagination
- Cloud File removed button loads on entering widget
- Offline Queue removed button loads on entering widget
- Add Refresh and Progress bar Offline Queue
- Bad configuration now prompts the user to create new config or to delete bad CID
- Offline File Queue UI modified, order of table changed and cleaned
- On-Enter functionality added to many widgets for submit functionality
- MCID deletion confirmation
- Updated deploy staging
- Updated Extended details to handle data set with filters
- Updated Extended details to handle to handle Pagination

FIXES
-----

- Fixed crash in offline queue
- Added missing functionality to UI of Kill Process
- Logging clean up throughout front end widgets
- Config Manager Crash liable not present fix
- On key down onchange input fix
- Extended details fix on refresh call not loading all of data sets
- Device load time and size fixed issue wasn’t updating on every service call

CODE REVIEW
-----------

- login
- Member CID
- Offline Queue
- Remote Explorer Table
- CrowdStrike Detection
- Extended Details
- Configuration Manager

SHA256 CHECKSUMS
----------------

================================================================  ===========================
4b0e75bff4bc0af5bbae830b5cedb1158fd193f57d3d6a0ec6c047f429bb8ac9  Peregrine.exe (Windows)
3d63bdfc45aecccd53cc82a65758b6ff09761564a429f5205882db5a2854ce92  peregrine-mac.tar (Mac x86)
================================================================  ===========================
