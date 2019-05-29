Control 10.1: Ensure Regular Automated Backups
==================================================

Ensure that all system data is automatically backed up on a regular basis. 

Category
________
Technical

Purpose
_______
A backup is a duplicate of a computer system’s data. If an attacker breaches a network or computer system, their first step will often be to change system configurations to ensure they have continued access in the future. In the process of doing so, attackers will sometimes make subtle alterations to data that can jeopardize an organization’s effectiveness at a later date. Backups also help to protect against many types of malware, including newer variants such as ransomware and destructive malware, which may encrypt or simply delete an organization’s data. 

Backups also help to harden an organization against natural disasters like fire and floods. Additionally, over time, systems will fail and a plan needs to be in place to make sure that a business can recover from whatever incident occurs. Automated backups taken on a regular basis are a key component of an enterprise disaster recovery plan.

Automation
__________
This Sub-Control is entirely automatable with very little effort on a Windows 10 system. Configuring this Sub-Control enterprise-wide across all systems can take a fair amount of IT knowledge to initially install. Backups are often setup by configuring an application to backup information to an external computer dedicated to backups, or to an external hard drive.

Guidance and Tools 
__________________
Most operating systems come with built-in backup programs and utilities, which will need to be properly installed, setup, and configured. It is best practice to manually check enterprise backups from time to time to make sure that backup systems are working as intended, and can actually be utilized in case of a disaster. The following are examples of free backup utilities: 

* Microsoft Backup and Restore: A backup utility tool installed on Microsoft operating systems (https://support.microsoft.com/en-us/help/17127/windows-back-up-restore).
* Amanda Network Backup: Free, open source backup tool (http://www.amanda.org).
* Bacula: Open source network backup and recovery solution (http://blog.bacula.org).

*Step-by-step instructions for implementing this Sub-Control can be found in*: :ref:`Configuring Microsoft File History`