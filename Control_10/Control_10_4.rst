Control 10.4: Protect Backups
=============================

Ensure that backups are properly protected via physical security or encryption when they are stored, as well as when they are moved across the network. This includes remote backups and cloud services. 

Category
________
Technical, Procedural

Purpose
_______
Backups can help an enterprise recover from a variety of disaster situations, be they the cause of malicious actors or accidents. Yet backups can be physically and digitally targeted by attackers looking to hurt an enterprise. Backups that are connected to a network can be altered or deleted by malware, and physical backup drives can be stolen or suffer fires, floods, and other natural disasters. Backups need to be protected from these threats in order to be useful when the time comes. Digital mitigations include authenticating users before access and encrypting backups. Physical mitigations include keeping backup drives locked away from thieves, and also outside of the same fire zone. This means that if a fire or flood were to strike an organization’s physical location, the backups would not be affected. This is sometimes accomplished by using third-party backup services to store data offsite. These backups need to be protected as well.

There are two primary groups of threats to backups: digital and physical. Digital threats include local and remote attempts to access backups without being properly authenticated. Additional issues include altering or deleting backups. Physical threats include theft of physical backups or natural disasters (e.g., fires, floods).

Automation
__________
This Sub-Control can be somewhat automated. Third-party services can use a virtual private network (VPN) when backing up enterprise information to an offsite server. Microsoft’s BitLocker can encrypt any backups stored on a system. Physical protection of backups cannot be automated. 

Guidance and Tools 
__________________
Beware – encryption software can be dangerous if the password or encryption key is forgotten. If the password or key is lost, any enterprise data encrypted under that password or key will be unrecoverable. 

* Veracrypt: This tool is an open source free utility that provides full disk encryption and can also encrypt removable drives, such as those used for backup (https://www.veracrypt.fr/en/How%20to%20Back%20Up%20Securely.html). 
* EaseUS: This free program can encrypt system images (https://www.easeus.com/backup-software/tb-free.html).

*Step-by-step instructions for implementing this Sub-Control can be found in*: :ref:`Enabling BitLocker`  
