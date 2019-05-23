Control 16.8: Disable Any Unassociated Accounts
===============================================

Disable any account that cannot be associated with a business process or business owner. 

Category
________
Technical 

Purpose
_______
Extraneous accounts can be used to attack the system they are associated with, but also to compromise other nodes on a network. These accounts can be created on accident, for testing purposes, or be leftover accounts from contractors or employees no longer employed at an organization. Attackers often find and exploit legitimate, but inactive user accounts, and use them to impersonate legitimate users. When this occurs, it makes tracking the activities of attacker behavior quite difficult for those responding to a breach or performing forensic analysis. This Sub-Control states the need for disabling unassociated accounts but not deleting them. Deletion is not recommended as this will not preserve the audit trail and hamper any future computer incident investigations.

Unassociated accounts are often known as “stale” or “ghost” accounts on a system, and are a weak link for attackers. Accounts that have not been used by an employee are valuable accounts for an attacker to overtake. This is due in large part since the original account owners are not actively using the account, so it is difficult for an enterprise to notice if the account is being used maliciously.

Automation
__________

This Sub-Control is not entirely automatable. Products and scripts can be written to highlight suspect accounts, but the ultimate decision on whether accounts should be disabled may need to be made by a human.

Guidance and Tools 
__________________

Regardless of the edition of Windows 10 that is in use, all local and remote accounts on enterprise computer systems should be regularly checked and audited. This also extends to smartphones, network appliances, and any system that enterprise utilize accounts for user access. 

* Step-by-step instructions for implementing this Sub-Control can be found in*: Viewing Accounts on a Windows 10 System. 
