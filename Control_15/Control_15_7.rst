Control 15.7: Leverage the Advanced Encryption Standard (AES) to Encrypt Wireless Data 
======================================================================================

Leverage the Advanced Encryption Standard (AES) to encrypt wireless data in transit. 

Category
________
Procedural

Purpose
_______
The Advanced Encryption Standard, or AES, is an algorithm used encrypt information standardized by the United States Government in 2001. It is considered a modern, strong cipher that has withstood attempts to break it for years. This purpose of this Sub-Control is to make sure that an organization’s wireless traffic is strongly encrypted. AES is built into most wireless access points, or wireless routers, that can be bought at major electronics stores. AES is utilized with Wireless Protected Access version 2, or WPA2. Using Wireless Equivalent Privacy (WEP) or Wireless Protected Access (WPA) version 1 does not meet this Sub-Control, as AES will not be the algorithm used to encryption wireless information. Both WEP and WPA also have other significant flaws and should not be used. It is easier for an attacker to sniff wireless communications than wired communications, and by properly setting up AES, anyone on the wireless network will not be able to understand the transmitted network traffic.

Automation
__________
This Sub-Control is entirely automatable for many types of wireless traffic, including WiFi. Simply selecting the proper configuration settings on a wireless access point will make sure AES is being used for all devices that connect to the network. 

Guidance and Tools 
__________________
AES should be enabled for all wireless networks within an enterprise. This includes 2.4 Gigahertz (GHz) and 5 GHz, as these are two completely separate wireless networks that must be properly configured. It’s not possible to list all of the models of wireless routers, but the following links are provided to show how to enable encryption on some of the most common wireless access points from United States ISPs. 

* Comcast: Comcast provides information on how to configure their modem (https://www.xfinity.com/support/articles/change-wifi-security-mode).
* Verizon: Verizon provides guidance for how to configure their router (http://www.verizon.com/support/smallbusiness/internet/fiosinternet/networking/setup/zyxeladapters/128755.htm). 
* AT&T: AT&T customers can configure their network devices via this guidance (https://www.att.com/esupport/article.html#!/u-verse-high-speed-internet/KM1049997?gsi=1ysnu3). 

*Step-by-step instructions for implementing this Sub-Control can be found in*: Identifying if a WiFi Connection is Using AES. 
