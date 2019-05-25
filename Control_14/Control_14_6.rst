Control 14.6: Protect Information Through Access Control Lists 
==============================================================

Protect all information stored on systems with file system, network share, claims, application, or database specific access control lists. These controls will enforce the principle that only authorized individuals should have access to the information based on their need to access the information as a part of their responsibilities.

Category
________
Procedural

Purpose
_______
Different types of employees will need varying levels of access within an enterprise. Users with more sensitive roles and job responsibilities may need additional access, such as Human Resources and Finances, whereas users with more simple workplace needs will necessitate fewer permissions. This means that access to data, systems, and files should be provided according to business needs. Administrative or super user access should not be provided to all employees. 

Users with large amount of system access can easily make accidental changes that affect multiple users and systems. Sometimes these changes will not be easily recoverable, like deleting an entire network drive. Another scenario worth considering is if a user with broad privileges has their accounts compromised, the attacker would be able to access everything that user is able to access.

Automation
__________
User access can be accomplished through Windows Active Directory Group Policy. This functionality can also be controlled through Windows Intune. Not all systems will be domain joined – for instance firewalls will also need access control decisions made and enforced. Ultimately access control decisions will need to be made by a human. 

Guidance and Tools 
__________________
Correctly configuring access control on a computer system can be a complex task. 

* Qualys Browser Check: A tool to check if a browser is up-to-date with all its patches (https://browsercheck.qualys.com).
* OpenVAS: A tool to scan systems to check security baselines (www.openvas.org).

.. image:: _static/BenchmarksLogo.png

CIS offers free PDFs with configuration guidelines for 100+ technologies, which can be used to correctly configure users, applications, and other access control lists (https://www.cisecurity.org/cis-benchmarks). 