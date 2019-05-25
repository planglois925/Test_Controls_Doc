Control 12.4: Deny Communication Over Unauthorized Ports 
==============================================================

Deny communication over unauthorized TCP or UDP ports or application traffic to ensure that only authorized protocols are allowed to cross the network boundary in or out of the network at each of the organization’s network boundaries. 

Category
________
Technical

Purpose
_______
The overarching CIS Control 12 details precautions that should be taken for boundary defense, which is the notion of establishing and protecting a perimeter around an organization’s externally facing networking equipment. Sub-Control 12.4 manages how communication is controlled on networking devices, such as firewalls. In order to accomplish this, the firewall configuration and ruleset in use should be carefully reviewed, monitored, and curated. If an enterprise-grade firewall is not in use, many of the dual-use modems/wireless access points from the ISP will often have a firewall built into the system which can be enabled.

A large majority of attacks launched against an organization will attempt to enter networks through a firewall. Firewalls often act the default entry point into a network and can deny communication over certain ports. Because of this they are under nearly constant attack and must be configured properly to protect the organization's assets sitting behind them. A firewall is typically envisioned to protect against basic attacks using a variety of protocols such as Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), and Network Time Protocol (NTP).

Automation
__________
Expensive enterprise tools can be purchased that require skilled technical staff to monitor and verify router configurations. This is generally not automatable for small- to medium-sized businesses.

Guidance and Tools 
__________________
It is not possible to list all of the models of networking equipment. The following links are provided to show how to enable the built-in firewalls on some of the most common modems/wireless access points from United States Internet Service Providers (ISPs): 

* Comcast: Comcast provides information on how to configure their modem (https://www.xfinity.com/support/articles/advanced-xfinity-wireless-gateway-features). 
* Verizon: Verizon provides guidance for how to configure their router (https://www.verizon.com/support/residential/internet/security/home-network).
* AT&T: AT&T customers can configure their network devices via this guidance. (https://www.att.com/esupport/article.html#!/smb-internet/KM1188420?gsi=xDPL7tW0).

.. image:: _static/BenchmarksLogo.png

CIS offers in-depth guidance for many types of firewalls and other network appliances (https://www.cisecurity.org/cis-benchmarks). 