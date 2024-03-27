Peregrine Menu overview
=======================

*This document describes the various features of MPG Peregrine from the
logged-in user’s perspective. It describes the function of each of the
tabs within the Peregrine UI’s Menu system.*

* **Host Explorer**: view of each system in the currently selected CID/tenant. Allows you to identify and select systems that you want to perform actions on, as well as give you a brief overview of system status, IP configuration, username, and identifying the last time a system was online or is currently online, as shown by blue icon color.
* **Host Extended Details**: has over 50 unique properties for each system (Host Explorer only shows 15).
* **CID & Configuration Manager**: allows you to configure and select between different CrowdStrike CIDs (tenants) within an organization and allows you to configure and switch between CrowdStrike Organizations/Clients very quickly. Configuration and CID information is stored within encrypted .ENV files on your system.
* **Cloud Files Manager**: allows you to view a list of the files that you either uploaded or downloaded to/from systems within the currently selected CrowdStrike CID/Tenant. You can view file properties and delete files too.
* **Offline RTR** **Queue**: displays a list of actions that have been attempted in the last 14-days where the system was not online. Gives a holistic view of system status, whether completed, still outstanding, etc. If the action does not complete in the 14-day time frame, you will have to reinitiate the action if it is still desired.
* **Zero Trust Assessment:** Shows the Zero trust score (as assigned by CrowdStrike) for each host in the current CID/Tenant. You will not see this information if you are in “Flight Control,” you must select an individual CID/Tenant. It allows you to search/filter systems that are below a specific score.
* **Contain/Uncontain**: allows you to select systems that you would like to perform the CrowdStrike Contain operation on, such as if they have some type of vulnerability and you want to do some type of remediation on them. Once you are finished you can Uncontain/Lift_Containment them as a group too.
* **IP config/Netstat**: allows you to get IP or Netstat information for the specified systems.
  .. Note::  
    Works on all 3 OS (Windows, Linux, and Mac).
* **Run Commands**: allows you to run command line scripts or Shell commands on selected systems, based on the operating system selected. Information/commands that you can run will change accordingly.
  .. Note::  
    Works on all 3 OS (Windows, Linux, and Mac).
    Your ability to run scripts may be limited by your CrowdStrike Access.
* **RTR Manager**: an advanced script running management tool that allows you to run large, more complex scripts against multiple machines.
  .. Note::  
    Works on all 3 OS (Windows, Linux, and Mac).
    Your ability to use RTR Manager may be limited by your CrowdStrike Access.
* **File Explorer**: allows you to view files, upload files, and delete files from a host.
  .. Note::  
    Works on all 3 OS (Windows, Linux, and Mac).
    This is a single host action.
    Your ability to run File Explorer may be limited by your CrowdStrike Access.
* **Windows Registry**: allows you to view and update, upload, or delete registry keys in Windows Hosts only.
  .. Note::  
    Works on Windows Only.
    This is a single host action.
    Your ability to run File Explorer may be limited by your CrowdStrike Access.
* **Task Manager**: allows you to review Processes, Services, and Scheduled Tasks. The Process list is read/write. Services and Scheduled Tasks are read only.
  .. Note::  
    Works on all 3 OS (Windows, Linux, and Mac).
    This is a single host action.
    Your ability to run Task Manager may be limited by your CrowdStrike Access.
* **Kill Process by Name**: allows you to kill a process currently running on all selected systems.
  .. Note::  
    Works on all 3 OS (Windows, Linux, and Mac).
* **CrowdStrike Detection**: allows you to simulate a vulnerability happening on a system, which will appear in your CrowdStrike portal. This CrowdStrike simulation does a test against a tenant to make sure that all the sensors are correctly set up and installed.
