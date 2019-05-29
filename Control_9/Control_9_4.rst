Control 9.4: Apply Host-Based Firewalls or Port-Filtering
=============================================================

Apply host-based firewalls or port-filtering tools on end systems, with a default-deny rule that drops all traffic except those services and ports that are explicitly allowed. 

Category
________
Technical

Purpose
_______
Computers are already setup with a default set of networking features right out of the box. This is typically a permissive set of configurations that allows computer systems to connect to whatever resources average users need. Host-based firewalls help to manage these network configurations, block external unsolicited attempts to connect to a computer system, lessen the impact of malware, and log network traffic for future analysis. Indeed, it is easier to download malware onto an enterprise computer if there is no firewall in place. Malware installed on an enterprise system can pilfer or destroy sensitive enterprise data, perform a Denial of Service (DoS) on various systems, or look to infect other aspects of the network. By properly configuring the built-in firewall an enterprise can help to reduce the ways that a system can be attacked. Additionally, it can help to stop downloaded malware from communicating home and work to prevent its installation in the first place.

Automation
__________
This Sub-Control is completely automatable within Windows 10 Pro.

Guidance and Tools 
__________________
Properly enabling the firewalls built into operating systems goes a long way towards properly implementing this control. If a computer is joined to a domain, the built-in firewalls can be automatically configured across all the computers within an enterprise network. Windows 10 comes with a firewall that will help to implement this Sub-Control. Third-party solutions are also available that can accomplish the same tasks for Windows and also support other platforms.

* Windows Defender Firewall with Advanced Security: This built-in host-based firewall helps any Windows 10 Pro user meet this Sub-Control (https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-firewall/windows-firewall-with-advanced-security).  
* Check Point Zone Alarm: This is a popular free firewall that can be installed on enterprise computer systems (https://www.zonealarm.com/software/free-firewall). 

.. image:: _static/BenchmarksLogo.png

CIS offers free configuration guidelines for common operating systems and their firewalls (https://www.cisecurity.org/cis-benchmarks).

*Step-by-step instructions for implementing this Sub-Control can be found in*: :ref:`Enabling Windows Defender Firewall`
