Control 16.9: Disable Dormant Accounts
==========================================

Automatically disable dormant accounts after a set period of inactivity. 

Category
________
Technical, Procedural


Purpose
_______
System and user accounts establish identity and access on information systems. Operating system privileges and granular file permissions can be assigned to individual users and groups of users (i.e., roles). When an organization is using Active Directory and domain controllers, each employee is generally assigned an account and assigned roles for what they are allowed to do within an organization’s entire network architecture. Local accounts unique to a system are often also utilized. When employees leave an organization, or even change organizational units, their privileges are removed. Yet it is possible to go a step further and automatically disable accounts after a predetermined period of time. Deleting accounts is not always recommended as this may disturb user, system, or application logs, or other information that may be needed to audit user activity in case an incident is discovered in the future. 
Dormant accounts are often known as “stale” or “ghost” accounts on a system, and are a weak link for attackers. Accounts that have not been used by an employee are valuable accounts for an attacker to overtake. This is due in large part since the original account owners are not actively using the account, so it is difficult for an enterprise to notice if the account is being used 


Automation
__________

Products and scripts can be written to highlight suspect accounts, but the ultimate decision on the length of time before an account should be disabled will need to be made by a human.  

Guidance and Tools 
__________________

There is no standard for the time interval before inactive accounts should be disabled. The length of time is sometimes 15 – 30 days, whereas others recommend 90 days. Enterprises requiring a higher level of security should utilize shorter timeframes. 

* Step-by-step instructions for implementing this Sub-Control can be found in*:  Viewing Accounts on a Windows 10 System. 
