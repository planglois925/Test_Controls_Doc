Control 13.2: Remove Sensitive Data or Systems Not Regularly Accessed by Organization
=====================================================================================

Remove sensitive data or systems not regularly accessed by the organization from the network. These systems shall only be used as stand-alone systems (disconnected from the network) by the business unit needing to occasionally use the system or completely virtualized and powered off until needed. 

Category
________
Technical


Purpose
_______
A breach of sensitive enterprise data and systems can cost time, money, and bring an organization out of compliance with local laws governing sensitive information. Sensitive data and computer systems infrequently accessed may not receive the regular maintenance and attention necessary to properly manage them. Therefore, systems that are infrequently used should be removed from service across the entire enterprise network. This helps to reduce enterprise attack surface leaving fewer systems that can be targeted. Older and infrequently used systems may fall into disrepair. These systems are not likely to receive regular software updates, which means the operating system and applications will likely contain vulnerabilities that can be exploited to access the system and any data. 

Automation
__________

There is no way to automate the implementation of this Sub-Control. Individuals will be needed to manually label sensitive data, and identify which systems store that sensitive data. Putting this Sub-Control into place will often require a hardware asset inventory as detailed in Sub-Control 1.4, alongside a sensitive information inventory as detailed in Sub-Control 13.1. 

Guidance and Tools 
__________________

Systems that are irregularly accessed and maintained should not be network connected while hosting sensitive enterprise information. If the systems are necessary to ensuring the goals of the organization, consider attempting to use them in a non-networked fashion or virtualizing the system.