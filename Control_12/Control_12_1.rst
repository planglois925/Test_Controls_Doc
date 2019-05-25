Control 12.1: Maintain an Inventory of Network Boundaries
==============================================================

Maintain an up-to-date inventory of all of the organization’s network boundaries. 

Category
________
Technical

Purpose
_______
Network boundaries define how data flows and traverses an enterprise network. Wired and wireless boundaries will exist, alongside logical boundaries. Logical boundaries sometimes include subnetworks (e.g., subnets) or virtual local area networks (vLANs). Generally, information cannot flow from one subnet to another without a networking device such as a firewall or router acting as a gatekeeper. This establishes trust boundaries between network segments. Therefore, a survey should be conducted to understand current trust boundaries in an enterprise network.

Understanding network boundaries can be challenging in a network that developed organically. The simplest example of a network boundary is the demarcation between a wireless and wired network. Another commonly seen example of a network boundary is the external network, and the internal intranet which generally is not accessible from outside of the trust boundary. Additionally, another important boundary to keep in mind is when a single organization has multiple physical locations. Often IT will work to logically connect all of their physical locations together. 

Specifically noting which networks are within a trust boundary, and then regularly checking them helps to prevent from accidentally trusting an untrustworthy device or network component. For instance, public users such as customers should not be granted access to the intranet, which often contains sensitive enterprise information.

Automation
__________
This Sub-Control is generally not automatable. System owners and administrators will need to manually annotate and define network boundaries. This task needs to be performed on a fairly regular basis. 

Guidance and Tools 
__________________
Network scanning and monitoring tools can help test predefined network boundaries. Over time, internal networks can be misconfigured and the networking tools can help to test of network segments are actually segmented.  

* Nmap: Famous multipurpose network scanner, used by system administrators and hackers across the world to identify which devices are connected to your network (https://nmap.org). This tool can identify network devices, ports, and simple configuration settings. Only scan networks you don’t own, as that is often impolite, and in many cases illegal. 
* ZenMap: This tool builds on top of Nmap, and puts a graphic user interface on top of it to make the tool easier to use for those who do not feel comfortable using the command line (https://nmap.org/zenmap).
