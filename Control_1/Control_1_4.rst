Control 1.4: Maintain Detailed Asset Inventory
==================================================

Maintain an accurate and up-to-date inventory of all technology assets with the potential to store or process information. This inventory shall include all assets, whether connected to the organization’s network or not. 

Category
________

Procedural, Technical 

Purpose 
_______

An accurate and up-to-date inventory of computer systems within a network is often the first step in securing an enterprise. This list of information systems is known as a hardware asset inventory. Having a definitive list of what hardware is supposed to be part of a network enables comparison against the list of systems that are actually in place. This allows for the identification of unauthorized devices that should not be connected. A hardware asset inventory also helps define what an organization needs to protect. 

An asset inventory often extends beyond what is solely connected to the network. Many organizations utilize older smartphones, laptops, networking gear, and other technology that may not be connected, or even powered on, yet might still contain sensitive information if the data is exfiltrated outside of the network. In addition to physical systems, many enterprises use third-party services for website hosting or email that are hosted in the cloud. Accordingly, any third-party services and cloud platforms should be included in the asset inventory. Examples of what to track include:
* General computer workstations, laptops, phones, tablets;
* Physical systems and devices operated or possibly owned by another organization that are connected to the enterprise network (e.g., Point of Sale devices); and 
* Systems used by an organization that are cloud-hosted.

Although asset management does not specifically mitigate any threats, it is the foundation for a large majority of cybersecurity activities. Cybersecurity expert Daniel Meissler points out that `If You're Not Doing Continuous Asset Management You're Not Doing Security <https://danielmiessler.com/blog/continuous-asset-management-security/>`_, and argues that it is one of the most important aspects of cybersecurity. Meissler states that lacking this asset inventory is one of the main reasons that companies get breached. If you don’t know what you are supposed to be defending, you can’t properly defend it. 

Automation
__________

This Sub-Control is automatable but not every enterprise will have the resources to do so. Accordingly, many organizations will perform manual asset tracking by hand. Manual asset tracking often times uses a spreadsheet with predefined columns and rows to help companies track the right data. It is often cumbersome, prone to error, and takes a good deal of time to get right – yet even an inventory with some holes in it is better than no asset inventory at all. Automated asset inventory can include using a web application or program installed on an in-house computer to store and track information within a database. It can also include a scanning tool that will automatically query devices with a variety of methods. There is a hybrid solution, where organizations use free or open source tools, like those mentioned below, and copy the results from those scans into a spreadsheet or other database. 

Guidance and Tools 
__________________

A variety of software is available in the market to solve this problem, but it may be too expensive for everyone. The following is a list of free tools and software which can help to ease the burden of asset tracking:
* Nmap: Famous multipurpose network scanner, used by system administrators and hackers across the world to identify which devices are connected to a network (https://nmap.org). Be careful to only scan networks for which permission was explicitly given. It is often impolite, and in many cases illegal, to scan networks owned by others. 
* Spiceworks: This is a free IT inventory and asset management software to identify devices and software on a network (https://www.spiceworks.com).
* ZenMap: This tool utilizes Nmap and places a user interface on top of it to make the tool easier to use for those who do not feel comfortable using the command line (https://nmap.org/zenmap).
* CIS Hardware Asset Tracking Spreadsheet: This free spreadsheet is created by CIS to help track enterprise systems and other assets. It can be modified as needed to meet an enterprise’s unique needs. The primary elements within the spreadsheet are also described within the relevant appendix.

*Step-by-step instructions for implementing this Sub-Control can be found in:* Hardware & Software Inventory.

