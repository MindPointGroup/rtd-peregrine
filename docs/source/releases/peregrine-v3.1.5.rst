Release Notes Peregrine™ v3.1.5
==============================

============= =======================
Release date: 2024-08-23
Notes:        Peregrine 3.1.5 is a recommended install for all users.
============= =======================

UPDATES
-------

- Sort Table by first column on load of each module
- Update "Offline Queue Manager" functionality to allow user to see more information in the table such as stdout and stderror information.
- Add Fields to Table Queue Offline Table
- Update Queue Offline when deleting a record to not call get Queued records and just delete the removed request from the current record set
- Update output information for Queue Offline in Run Commands and RTR Manager to make more readable for users
- Add Stdout and Stderror to table info
- Add sorting and searching capabilities into Task manager processes and start up services
- Add "Pending" to Filter Dropdown
- Develop Custom Table with Pagination and Sorting
- Sort Zero Trust Right Side Table by Host Name on load
- Update Batch Test Crowdstrike Detection to use batch function
- Update go falcon API
- Upgrade Fyne SDK to 2.5.0
- Upgrade Peregrine Framework to Golang 1.22.5


FIXES
-----

- Fix issues related to Upgrading Fyne SDK 2.5.0
- Fix KeyEvent key listener bug (Caused keyboard input lag)
- Fix Registry Path not maintaining state when canceling a delete
- Fix Task Manager (Linux) Button Control 
- Fix Task Manager (Mac) Button Control 
- Fix Task Manager (Windows) Button control 
- Ui Fix for small screen, Peregrine when loading Host Explorer Screen application was bleeding off of screen
