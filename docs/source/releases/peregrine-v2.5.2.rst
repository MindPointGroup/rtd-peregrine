Release Notes Peregrine v2.5.2
==============================

============= =======================
Release date: 2024-01-16
Notes:        Peregrine 2.5.2 (RC1). Many new updates as detailed below. 
============= =======================

Member CID:
-----------

- Improved UX when switching MCID
- Removed Ready Only Form Elements on Switch CID.
- Hardened “No CID” Condition when user tries to use one.
- Conformation dialog on adding CID when user is not allowed.
- Adjusted Verbiage for Forbidden Error Handler
- Read only Privileges Service Layer Stood Up
- User Cancel operation for add new Fixed bug form not clearing MCID Label.
- Precheck for CID when adding new CID dialog fix
- No Cid Operation when user adds Client with no cid
- Fixed Selection of MCID not maintaining selected state

Client Configuration Manager:
-----------------------------

- Improved UX when switching Configuration Files
- Bug fixes for check current .env is not in use w dialog when adding New .env.
- Bug fixes for utility to append and reload .env files into client/host list after users adds new .env file.
- Setup Error Handler Utility when NO CID is Required
- User Cancel operation for add new Fixed bug form not clearing MCID Label.
- Fix Precheck for adding new client checks CID against account Dialog was not displaying.
- No Cid Operation when user adds Client with no cid fix no dialog display under certain user condition.
- Fixed Selection of Configuration file not maintaining selected state

Task Manager:
-------------

- OnSwitch of OStype Clear last session w more than 1 device selected
- Adjusted Refresh UI for Refresh
- Adjusted UI for Clear
- Adjusted Refresh Ui for Back Operation
- Code Review/Clean

Remote File Explorer:
---------------------

- Adjusted Refresh UI for Refresh
- Adjusted UI for Clear
- Adjusted Refresh Ui for Back Operation
- Fixed no OStype on First Load operation Buttons are disabled if no device is selected
- Fixed no OStype on Walk Directory
- Fixed No OsType on Refresh
- Fixed if Input Address is Blank Dialog will display informing user of condition
- Fixed if no Device is present Dialog will display informing user of condition
- Remove Computer from input path on load
- Upload if no Device is present Dialog will display informing user of condition
- Error handler precheck for upload success
- Removed duplication of refresh widget
- Code Review/Clean

Ipconfig Batch:
---------------

- Stood up Batch operation for Ipconfig
- Service layer of operations written for Batch operations

Activation Login:
-----------------

- Fixed Main window when progress bar displays between windows traversing crash
- Fixed Selection of MCID and Configuration file not maintaining selected state

CrowdStrike Detection:
----------------------

- Dialog Warning CrowdStrike User they are about to run Detection

Environment Configuration:
--------------------------

- Global Release Version setup
- Phone Home Service written for Global Release Version

Debug Status:
-------------

- Added to info Bar

CICD:
-----

- Build out YAML operations
- Setup Branch triggers
- Detect tag in Git Actions
- Bug Fixes for Mismatch
- Stood Up Permission
- Stood up allow action for create-release
- Testing
- Fix Formatting issues
 
Code Review:
------------

- ActivationLogin.go
- ClientHostManager.go
- MemberCIDContainer.go
- remoteExplorerTableWindow.go
- main.go
- progressBarUtil.go
