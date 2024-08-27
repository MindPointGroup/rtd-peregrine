Release Notes Peregrine™ v2.6
========================

============= =======================
Release date: 2024-01-29
Notes:        Peregrine 2.6 (RC2) is our GA release candidate. 
============= =======================

UPDATES
-------

- Setup Ipconfig/netstat admin service call
- Updated Ipconfig Batch service update Front-end
- Updated Batch code that allows non-Admin to run Ipconfig/Netstat
- Updated Batch Crowdstrike call with Device Object to allow hostname to be added on the service level
- Updated Ipconfig clear dropdown after device removal
- Updated Contain/ Uncontained Clear all on Device removal
- Updated clientHostManagerContainer.go clear and maintain state
- Updated Maintain State of datasets, touched input and output fields through out all 17 widgets
- Updated Maintain Focus of current user selected widget
- Updated Menu name
- Allow Peregrine to identify what Crowdstrike scope the user has based on their provided credentials
- Addition of copy and refresh buttons to contain/uncontain

FIXES
-----

- Fixed Update Windows tab issue not clearing after Linux and Mac Selection
- Fixed MemberCID No Cid on Client .env file when adding new and current is selected
- Fixed Removed Ipconfig old single service replaced with Batch ipconfig service
- Fixed Add CID form not displaying after forbidden error returned
- Fixed current selected CID not deleting
- Fixed Several error handling bugs
- Fixed RTR/RunCommands persistence and clearing

CODE REVIEW/CODE CLEAN
--------------------

- Code review/clean & Removed unused Files
- Code review/clean Menu Item
- Code review/clean Activation Login
- Code review/clean Main.go
- Code review/clean Contain Uncontained
- Code review/clean Configuration Manager
- Code review/clean Host Explorer
- Code review/clean File Que Offline
- Code review/clean getRegedit
- Code review/clean getregoperations
- Code review/clean getremotefileexplorer
- Code review/clean getremotefilefolder
- Code review/clean global dialogs
- Code review/clean global search/variables
- Code review/clean Removed unused service layer code as well as updates to the sql dependencies
- Code review/clean Output layouts and UI Layouts
