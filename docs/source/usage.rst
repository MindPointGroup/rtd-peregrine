Usage
=====

Prerequisites
-------------

- **CrowdStrike Falcon API Access**:
    Peregrine™ works with your individual user API access to grant permissions for changes across your system. In order to use Peregrine you will need access to your organization’s CrowdStrike Falcon API, which includes your personalized API Key and Secret Key, provided to you by your CrowdStrike Admin. CrowdStrike has more information on how to create those keys at https://www.crowdstrike.com/blog/tech-center/get-access-falcon-apis/  
- **Operating Systems**:
    Currently Peregrine works on Windows machines with future plans for MacOS and Linux. Be sure to check out the download page for update and signup for notifications for those systems.

.. _installation:

Installation
------------

- Download MPG Peregrine at https://www.mpgperegrine.com/download
- Windows: create a folder and place Peregrine.exe in that folder. That's it!
- Mac: Coming soon.
- Linux: Coming soon.

Activating Peregrine™ for your organization
---------------------------------------

All Peregrine accounts require an organization account, with an invitation key, to be setup first. That Organization Account will then administer Seat Activation Keys to that organization's account. If this is your organization's first time activating Peregrine™, you will need both an Invitation Key (for portal access), and a Seat Activation key to activate your Peregrine™ desktop app.

Seats within an organization allow for a consolidation of endpoint counts, so your organization is not billed more than once for endpoints within your environment(s). We do not charge per seat with Peregrine™, so be sure to create keys for each seat in your organization that you would like to have access to Peregrine™.  

Obtaining an activation key to Create your Peregrine Portal Account:

#. Download the Program at https://www.mpgperegrine.com/download
#. Request an Invitation Key from https://www.mpgperegrine.com/  
#. Receive an email with link to download Peregrine and an Invitation Key (New Accounts)  
#. Signup for a Peregrine account at https://portal.mpgperegrine.com/signup

You will need to following to register your Organization: 

- First Name
- Last Name
- Email Address
- Company Name
- Invitation Key
- Set a Password

Once you are into the system you are ready to get Seat Activation Keys:

#. Create an Account Group
#. Add Seats  
#. Share each Activation Code with the appropriate team member. These are their Peregrine License Keys.  

Activating Peregrine™ for individual seats in your organization
-----------------------------------------------------------

If you are a part of a team already using Peregrine, activating your seat is quite simple.  

#. Obtain a Seat Activation Key from your Peregrine Administrator
#. Download at https://www.mpgperegrine.com/download
#. Save the file to the location on your system where you want the program to live. With Peregrine there are no install requirements, the program is ready to run right after you download it.
4. Run/Open the Peregrine Application
  The First time you run the program a folder will be created in the same location as the executable file. This folder will save your encrypted files for use with Peregrine.
5. Enter your Seat Activation Key in the License key field provided within the Peregrine desktop application.  
6. Click Submit to activate Peregrine.

Set up the Client 
----------------

Adding your CrowdStrike API User Identifications 

Under the CrowdStrike API Configuration Section: 

#. Cloud Type: Select the Cloud Used by your tenant
#. Client OD: Enter the CrowdStrike API Key
#. Client Secret: Enter the CrowdStrike API Secret Key
#. No CID: If No CrowdStrike API ID is available at this time, check this box to bypass this area
#. CID Nick-Name: Add an identifying name the CID - Client CID Name from your CrowdStrike Host Group
#. CID Number: Add the Client CID Number from your CrowdStrike Host Group
#. Configuration name:  Add a unique name to make this easier for you to remember
#. Enter a time to keep Log Files in days. The retention period is for how long log files are kept on your PC for Peregrine activities. These do not affect anything in CrowdStrike audit logs. We recommend 30 days to start.  
#. Leave Debug Mode unchecked
#. Click Save.  
  Your Credentials will be encrypted and saved for future use in the program.

Repeat this process if you have multiple CIDs to enter.

Congratulations!
----------------

You are up and running! Be sure to check-in over on our Discord Channel to connect with the peregrine Community with any questions, for tips and to share scripts and ideas for improving the platform! We look forward to hearing all about your experience with Peregrine™! Welcome aboard!  
