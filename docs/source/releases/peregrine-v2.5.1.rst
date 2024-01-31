Peregrine v2.5.1 Release Notes 
============================

============= =======================
Release date: 2023-12-11
Summary:      Peregrine update 2.5.1 is a bug-fix and UX improvement update for Peregrine. Much attention has been paid to improving the configuration experience as well as giving the user better feedback when their CrowdStrike configuration is causing problems. This release also does a better job of detecting online/offline status of endpoints. We recommend all Peregrine users update their Peregrine to 2.5.1 as soon as practicable. 
============= =======================

Member CID Fixes and Improvements: 
-------------------------------

- Improved UX when onboarding to stop form from pushing below the user's screen 
- Removed submit button 
- Hardened Condition check to check that CID is not in use w dialog when deleting 
- Conformation dialog on deleting CID 
- Setup Error Handler Utility 
- Read only Account Error Handler 
- User Cancel operation for add new 
- Precheck for CID when adding new CID 
- No CID Operation when user adds Client with no CID 
- Fixed Colon being passed into blank CID 
- Cred Check before .env is written to file 
- Clear Form operation 
- Hardened User Cancel delete operation 
- Setconfig Host fix 

Client Configuration Manager: 
---------------------------

- Bug fixes for check current .env is not in use w dialog when deleting 
- Bug fixes for utility to append and reload .env files into client/host list after users adds new .env file 
- Setup Error Handler Utility 
- Hardened User Cancel delete operation 
- Precheck for adding new client checks CID against account 
- No CID Operation when user adds Client with no CID 
- ON Client option 403 parent fix with No CID 
- No CID on current client check with current MCID check 
- Fixed Colon being passed into blank CID 
- Cred Check before .env is written to file 
- User Cancel operation for add new 
- Setconfig Host fix 

Activation Screen: 
-----------------

- Debug Fix for onChange of Debug selection 
- No CID Operation when user adds Client with no CID 
- ON Client option 403 parent fix with No CID 
- Empty CID for New User Operation 
- Fixed Colon being passed into blank CID 
- Setconfig Host file 
- Cred Check before .env is written to file 

RTR (Real Time Response) Manager: 
-------------------------------

- RTR Manager Copy All Across all OS types 
- Run Script bug fix 
- CrowdStrike Call: 
- Access Denied Service layer error Handled 

Authenticate Client: 
-------------------

- Removed Check to only change CID if it is not empty 

Host Explorer: 
-------------

- Online/Offline status fix 
- Fixed OS type Icon not displaying correct OS type 

Zero Trust: 
---------

- Zero trust multi thread with error handler crash fix 
- Function Class Updates to new classes from GoFalcon update 
- Built out UI New Table with query to search for overall score 

Cloud File Explorer: 
-----------------
- Sorting for table UI 

CrowdStrike Detection: 
--------------------

- Ui and logging updates 

Configuration File{.env): 
----------------------

- Converted Titles to Generics 

Dependencies: 
-----------

- GoFalcon updated to 2.33 and 4.2 

Code Review: 
----------

- Activationlogin.go 
- environmentConfiguration.go 
- clientHostmanager.go 
- menuItems.go 
- welcome.go 
- windowsElements.go 

Environment Configuration: 
------------------------

- Updated Encryption 

Online Status: 
------------

- Wrote new online status utility 
