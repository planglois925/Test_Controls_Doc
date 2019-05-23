Control 8.5: Configure Devices to Not Auto-Run Content
==========================================================

Configure devices to not auto-run content from removable media 

Category
________
Technical 


Purpose
_______
Removable media includes USB drives, memory cards, and external hard drives - just to name a few examples. These devices are commonly used to store photos, videos, and many types of enterprise data. Removable media is also one method used by attackers to install malicious software on computer systems. This attack method can be used to infect traditional enterprise workstations, but also computer systems viewed as secure since they lack a WiFi or Internet connection. Entirely banning the use of removable media is often impractical for businesses. If software on a USB device is allowed to automatically run, it may be able to install malware with limited to no user interaction.

Malware is software specifically designed to attack computer systems, devices, and data. Malware can enter an enterprise through any number of points such as email attachments, malicious apps, web pages, and USB drives. This Sub-Control was specifically included due to the emerging technique of dropping USB drives embedded with malware in parking lots or other areas where employees are likely to pick them up and plug them into enterprise systems. One academic study dropped 300 USB sticks around a school which resulted in ~50% of them being inserted into computers. Many were inserted into a computer within 6 minutes. 


Automation
__________

This Sub-Control is automatable natively in Windows 10 Pro. There is a setting within Windows 10 Pro that provides control on how content is run from removable devices. If a computer is joined to a domain, these policies can be deployed across all the computers in a network.

Guidance and Tools 
__________________

Removable devices should not be trusted. How enterprise systems treat removable devices is controllable via the AutoPlay within the Windows 10 Pro Control Panel. Configuring the devices to Ask Me Every Time will give administrators the ability to make this decision before programs are run.

*Step-by-step instructions for implementing this Sub-Control can be found in*: Configuring Autoplay on Windows 10 Pro

