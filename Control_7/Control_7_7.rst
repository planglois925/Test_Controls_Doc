Control 7.7: Use of DNS Filtering Services
==============================================

Ensure that only fully supported web browsers and email clients are allowed to execute in the organization, ideally only using the latest version of the browsers and email clients provided by the vendor. 

Category
________
Technical 

Purpose
_______
While the DNS can be difficult to grasp, the important details are relatively simple. DNS can be thought of as a phonebook for websites that translates a human understandable domain such as (www.cisecurity.org) to a series of numbers that a computer can understand (i.e., Internet Protocol (IP) address). Therefore, when a computer wants to connect to cisecurity.org, it uses DNS to look up where it can find example.com, much like how a phone book would be used to search a person’s name to get their phone number. And all of this happens transparently in the background when requesting a webpage, so that individuals to solely need to remember the domain name instead of complex IP addresses. 

This Sub-Control helps prevent enterprise infrastructure from connecting to known malicious servers that control, host, or distribute malware, or collect sensitive information. Many attackers will host a malicious domain like “evil.com” to enable malicious activities, such as tricking users into giving sensitive credentials (i.e., phishing) or control already infected systems. By using a DNS filtering service, an enterprise can ensure their systems are pointing to a filtered phonebook (DNS responses) that would not provide bad phone number to any known bad domains; thereby protecting an enterprise from being infected or communicating with malicious systems. 

Automation
__________
There are many ways that this Sub-Control can be implemented in an environment and it will mostly depend on how the enterprise is currently configured. This Sub-Control is completely automatable with the correct hardware and software being used in a network. Unfortunately, the implementation of this Sub-Control will likely require someone with specialized knowledge of networking and DNS, alongside an external trusted source for DNS information. 

Guidance and Tools 
__________________
Multiple organizations exist that provide DNS filtering. Some even provide this service free of charge such as Quad9. With a simple configuration change, enterprise systems will use the filtering service with little to no impact on an organization’s Internet browsing all the while blocking bad traffic. Accordingly, the following resources can be of assistance: 

* OpenDNS: Steps for setting up OpenDNS on Windows 10 (https://support.opendns.com/hc/en-us/articles/228007207-Windows-10-Configuration).
* Quad9: Steps for setting up Quad9 on Windows 10 (https://www.quad9.net/microsoft).  

