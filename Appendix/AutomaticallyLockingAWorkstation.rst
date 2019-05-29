Automatically Locking a Workstation 
===================================
*Applies to Sub-Control 16.11* 

In the Windows search bar with the magnifying glass icon, type local group to open the Local Group Policy Editor. 

.. figure:: _static/SearchingForLGPE.png
   :align: center

   Searching for LGPE 
   
The Local Group Policy Editor is shown below. 

.. figure:: _static/LocalGroupPolicyEditorHomeScreen.png
   :align: center

   Local Group Policy Editor Home Screen 
   	
Select *Computer Configurations* and then *Windows Settings*. 

.. figure:: _static/LGPEWindowsSettings.png
   :align: center

   LGPE Windows Settings 

Select *Security Settings* and then *Local Policies*. 

.. figure:: _static/LGPELocalPolicies.png
   :align: center

   LGPE Local Policies 

Select Security Options and then double click Interactive logon: Machine interactivity limit.

.. figure:: _static/SelectingInteractiveLogonSettings.png
   :align: center

   Selecting Interactive Logon Settings 
	
The CIS Windows 10 Benchmark recommends 900 seconds or fewer. Choosing 600 seconds is 10 minutes. 

.. figure:: _static/InteractiveLogonSettings.png
   :align: center

   Interactive Logon Settings 