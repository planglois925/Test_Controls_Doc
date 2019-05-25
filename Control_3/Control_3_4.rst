Control 3.4: Deploy Automated Operating System Patch Management Tools
=====================================================================

Deploy automated software update tools in order to ensure that the operating systems are running the most recent security updates provided by the software vendor. 

Category
________
Technical

Purpose
_______
Security patches are updates to a computer’s operating system (OS) or installed software applications, and are a basic part of IT maintenance. The patches the OS developers provide often contain new features, but also contain fixes to recently discovered security vulnerabilities. Over time, operating systems go “stale” and need to be updated. Without a constant stream of security patches, computer systems can be infected by malware that can read sensitive company data, or simply destroy it. Accordingly, patching systems is one of the primary ways an enterprise can protect itself from attackers. 

Automation
__________
Many modern operating systems already contain ways to natively manage security patches. Enabling native patch management can be done on a case-by-case basis or via a domain controller to manage enterprise systems (which is more common in larger organizations.) Software from external sources can also be installed on all enterprise systems which reports the current status back to a local server or cloud-based platform. The CIS Windows 10 Benchmark can be useful in showing users how to setup the operating system to automatically acquire and install updates. 

Guidance and Tools 
__________________
There are free products available to assist with patch management. By default, `Windows 10 is configured to download and install updates automatically (https://support.microsoft.com/en-us/help/12373/windows-update-faq)`_ unless that is modified by a user or administrator. 

* Itarian: This application offers a patch management solution for Windows (https://us.itarian.com/patch-management/free-windows-patch-management-software.php).
* Opsi: A more complicated solution that can help to manage both Windows and Linux platforms (https://www.opsi.org).

.. image:: _static/BenchmarksLogo.png

CIS offers PDFs with configuration guidelines for 100+ technologies (https://www.cisecurity.org/cis-benchmarks).

*Step-by-step instructions for implementing this Sub-Control can be found in*: Configuring Automated Operating System Patch Management via Windows Settings.

