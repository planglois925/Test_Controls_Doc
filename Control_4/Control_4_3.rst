Control 4.3: Ensure the Use of Dedicated Administrative Accounts
=====================================================================

Ensure that all users with administrative account access use a dedicated or secondary account for elevated activities. This account should only be used for administrative activities and not Internet browsing, email, or similar activities. 

Category
________
Procedural 


Purpose
_______
Accounts on a computer system can have different types and sets of privileges. The accounts with the highest access privileges are called administrative accounts. Other terms for administrative account include admin account or superuser accounts. These accounts grant access to all of a computer system’s data and functionality. It follows that protecting these accounts is of the utmost importance. If administrative accounts are abused or taken advantage of, they can be used to compromise an entire system and potentially the other computers connected to them via a network. For example, if an administrative account is used to browse the web, and accidentally downloads malware, the malware will be able to run on a computer with the highest levels of access.

Yet administrative accounts are needed for certain important tasks, such as installing new programs, updating the operating system, or adding new users. This Sub-Control states that administrative tasks need to be performed with a separate account solely dedicated to administrative tasks. Normal user accounts should be used for everyday business tasks, like using accounting software or performing market research via the web. If a vulnerability is exploited within a normal user account, the impact will be substantially less than if the same vulnerability is exploited under an admin account.
 
If someone is able to obtain administrative access on a computer system, they essentially have the keys to the kingdom. They will be able to steal passwords stored on the computer, which may be used in other computer systems or applications within a network. They will also be able to install a rootkit which is a type of malware that is sometimes undetectable, even by antivirus software. These types of information could compromise enterprise systems for months or even years. 

Automation
__________

This Sub-Control generally cannot be automated. Users must manually check to identify if their account is an administrator and establish separate administrative accounts.  

Guidance and Tools 
__________________

There is no standard that can be pointed to for how to keep everyday user accounts and administrative accounts separate. With that said, the following guidance can be useful: 

* Passwords should be different for everyday accounts and administrative accounts. 
* If multifactor authentication is not in use, the passwords for administrative accounts should follow current best practices for password strength. 
* Once a task is completed that required administrative access, make sure to immediately logout of the account.

**Step-by-step instructions for implementing this Sub-Control can be found in:** Identifying if an Account is an Administrator

