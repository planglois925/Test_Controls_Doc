Control 2.1: Maintain Inventory of Authorized Software
======================================================

Maintain an up-to-date list of all authorized software that is required in the enterprise for any business purpose on any business system.

Category
________
Procedural 

Purpose
_______
An accurate and up-to-date inventory of all company software is nearly as important as tracking the hardware inventory, as detailed in Sub-Control 1.4. By tracking the software being used on organizational assets, it is possible to ensure that only authorized software is installed. This is known as creating an authorized software inventory. Unauthorized software may include older versions of previously authorized software applications, or software installed by an employee, unbeknownst to the enterprise (sometimes referred to as shadow IT). Unauthorized software also includes any malware or malicious code installed by an attacker that gained access to an enterprise system or network. Understanding the software installed on a system helps organizations to define their software attack surface, and allow for a plan to be devised to remove that software

Software should be tracked for all enterprise systems and devices, even if they do not have network access. An old, unpatched application running on a non-networked system may be connected to the enterprise network at some point in the future. Old phones, laptops, networking appliances, and other technology that are rarely powered on may still contain sensitive information. In addition to physical systems, some companies may rely upon cloud infrastructure for email and data storage. Virtualized systems are another asset type that can contain sensitive enterprise data. Software associated with cloud-based and virtualized systems should both be included in a software asset inventory. Therefore, examples of software on different types of systems that should be tracked to comply with this Sub-Control include:

* Software pre-installed on the operating system, 
* Software installed by an organization, 
* Cloud infrastructure and applications, and 
* Virtual machines and their hypervisors. 

Although asset management doesn’t specifically mitigate any threats, it is the foundation for a large majority of cybersecurity activities. Daniel Meissler, a renown cybersecurity expert, points out that “If You’re Not Doing Continuous Asset Management You’re Not Doing Security”, and argues that it’s one of the most important aspects of cybersecurity. Meissler states that lacking this asset inventory is one of the main reasons that companies get breached. If you don’t know what you are supposed to be defending, you can’t properly defend it. Organizations interested in a stretch goal to help address future threats can consider implementing CIS Sub-Control 2.4, which suggests the following information to be tracked:

- name, 
- version, 
- publisher, 
- install date, and 
- operating system.

Automation
__________

This Sub-Control is automatable but not all organizations will have the resources to do so. Many small- to medium-sized organizations will need to manually curate their software inventory. Manually tracking software information is generally done with a spreadsheet with predefined columns and rows to facilitate proper data collection. It is often cumbersome, prone to error, and takes a good deal of time to get right. Yet even an incomplete inventory is better than no asset inventory at all. Automated software inventory management can include using a web application or program installed on an in-house computer to store and track information within a database. It can also include a scanning tool that will automatically query devices with a variety of methods. 

Guidance and Tools 
__________________
There is no universally agreed upon method for tracking software assets. A variety of software is available in the market to solve this problem, but may be too expensive for many. The following is a list of free tools and software which can help to ease the burden of asset tracking:

* Nmap: Famous multipurpose network scanner, used by system administrators and hackers across the world to identify which devices are connected to a network (https://nmap.org). Be careful to only scan networks for which permission was explicitly given. It is often impolite, and in many cases illegal, to scan networks owned by others. 
* ZenMap: This tool builds on top of Nmap, and puts a graphic user interface on top of it to make the tool easier to use for those who do not feel comfortable using the command line (https://nmap.org/zenmap).
* Spiceworks: This is a free IT inventory and asset management software to identify devices and software on a network (https://www.spiceworks.com).
* Netwrix: Variety of free tools to identify information about administrative access on any relevant systems (https://www.netwrix.com).
* OpenAudIT: Inventory applications and software on workstation servers and network devices (http://www.open-audit.org).  
* CIS Software Asset Tracking Spreadsheet: This free spreadsheet is created by CIS to help track enterprise systems and other assets. It can be modified as needed to meet an enterprise’s unique needs.

*Step-by-step instructions for implementing this Sub-Control can be found in*: Hardware & Software Inventory.

