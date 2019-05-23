Control 8.4: Configure Anti-Malware Scanning of Removable Media
====================================================================

Configure devices so that they automatically conduct an anti-malware scan of removable media when inserted or connected. 

Category
________
Technical 


Purpose
_______
Removable media includes USB drives, memory cards, and external hard drives - just to name a few examples. These devices are commonly used to store photos, videos, and many types of enterprise data. Removable media is also one method used by attackers to install malicious software on computer systems. This attack method can be used to infect traditional enterprise workstations, but also computer systems viewed as secure since they lack a WiFi or Internet connection. Entirely banning the use of removable media is often impractical for businesses. In order to combat this threat, enterprise systems should be configured to scan removable devices for malware before they can be read by users.

Malware is software specifically designed to attack computer systems, devices, and data. Malware can enter an enterprise through any number of points such as email attachments, malicious apps, web pages, and USB drives. This Sub-Control was specifically included due to the emerging technique of dropping USB drives embedded with malware in parking lots or other areas where employees are likely to pick them up and plug them into enterprise systems. One academic study dropped 300 USB sticks around a school which resulted in ~50% of them being inserted into computers. Many were inserted into a computer within 6 minutes. 

Automation
__________

This Sub-Control is somewhat automatable and is worth the expense to properly configure it. Windows Defender may not be able to scan removable media every time a new one is inserted, as scans will need to be configured and performed manually on every usage.

Guidance and Tools 
__________________

Windows Defender, a program built-into Windows, can perform a scan of removable media devices. This functionality is called a “custom scan” within the tool. Third-party tools can also be purchased to scan removable devices every time one is inserted in an automated manner. This Sub-Control should be implemented for of the systems within an enterprise.

*Step-by-step instructions for implementing this Sub-Control can be found in*: Scanning Removable Devices
