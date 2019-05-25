Control 4.2: Change Default Passwords
=========================================

Before deploying any new asset, change all default passwords to have values consistent with administrative level accounts. 

Category
________
Procedural

Purpose
_______
Default passwords are the passwords that ship with computers, applications, routers, and other equipment. Default passwords are a very common way for computer systems, devices, and applications to be hacked. Lists of default passwords for operating systems, applications, and devices are readily available on the Internet for anyone to download and try. Therefore, enterprise passwords need to be changed from the defaults to something that is not easily guessable or easily available from a search engine.

If a password for a wireless router is guessed, an attacker will be able to add and remove network devices, which will allow them to read sensitive enterprise information. To guess a router’s default password, it is often sufficient to identify the manufacturer and model of the device. Attackers may be able to find this information by viewing the device in person, or remotely based on a router’s wireless network name (i.e., service set identifier (SSID)), MAC address, and network scans. Lists are easily available online with the default passwords for wireless routers commonly used in small and home offices. If a password for an application, device, or other system is guessed, an attacker may be able to read the enterprise information stored there, or take control of the entire device. 

Automation
__________
Changing default passwords within software and network equipment is generally not automatable. Each software application or piece of network equipment has to be individually investigated and changed. 

Guidance and Tools 
__________________
One of the main issues with changing default passwords is the need to remember all of the passwords. Writing passwords down onto paper is considered an insecure practice. A better option is to use a password manager. Free examples include: 

* KeePass: This is an open source password manager (https://keepass.info).
* LastPass: This is a popular password manager for personal use (https://www.lastpass.com/password-manager).

.. image:: _static/BenchmarksLogo.png

The Benchmarks for an OS or application may contain passwords that should be changed, but not all products will have CIS Benchmarks, or have default passwords (https://www.cisecurity.org/cis-benchmarks).

*Step-by-step instructions for implementing this Sub-Control can be found in*: Changing the default password on Windows 10 Pro.


