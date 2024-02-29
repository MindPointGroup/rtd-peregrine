Release Notes Peregrine v3.0.1
========================

============= =======================
Release date: 2024-02-14
Notes:        Peregrine 3.0.1 is GA first bugfix update. Recommended install for all users. 
============= =======================

UPDATES
-------

- Device List Utilities.go wrote utility to manager OS type redirect on number of devices and OS type.
- Padding consistency CrowdStrike Detection, Kill Process by Name, Contain/Uncontain, Registry
- Padding consistency on ALL Device lists: Run commands, Ipconfig, Zero Trust, RTR Manager
- Kill Process by Name setup Placeholders for input fields.
- Widget In Use utility to maintain usage of each widget.
- All log.print wrapped in debug mode condition
- Added deployment yaml file for deploy to staging.
- New CICD work flow build yaml
- New CICD work flows add for windows Mac and Linux
- Service layer print line statements cleaned up for better navigation of terminal.

FIXES
-----

- Hold output state RTR script manager.
- Device List Utilities Widgets that are filtered by OS Type not maintaining state.
- Run Commands Clear only on selected tab.
- RTR Manager List panel not showing properly on tab selection.
- Run Commands Tabs not loading properly on Adding Script
- Reimplement save states on add for Run Commands.
- Device list redirect when removing all devices.
- Configuration Manager Adding or changing .env with multi .env was not clearing form
- Kill process by name error handler not returning error in output.
- RTR Delete issue.
- File request check std.Error
- getRemote file folder option crash
- dirty clean state ZeroTrust

CODE REVIEW/CODE CLEAN
----------------------

- Device List Utility
- Run Commands
