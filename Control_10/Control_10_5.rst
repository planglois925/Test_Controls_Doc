CIS Control 10.5: Ensure All Backups Have At least One Offline Backup Destination
=================================================================================

Ensure that all backups have at least one offline (i.e., not accessible via a network connection) backup destination. 

Category
________
Procedural, Technical


Purpose
_______
Over the past few years a new type of malware has become popular that prevents enterprises from accessing their own data. This malware requires affected organizations to pay money in order to regain access to their data, whereas a related form of this malware may instead block access and never provide it ever again. Malware that requires money to obtain access once again is called ransomware. Ransomware uses cryptography to block access to a system’s data via encryption. If the data is never provided back, it is considered destructive malware.

Besides user education and antivirus software, one of the best defenses against ransomware is backing up data to another system before there is a problem. But backups alone would not completely prevent this malware from accomplishing its goals. Typical backups may be connected to another system or network, meaning backup data can still be attacked. Therefore, regular backups should be stored in an unconnected, off-the-network, manner. 

Keeping offline backups helps organizations recover and restore systems when ransomware or destructive malware hits a system. A common way for this malware to get into a network is to be installed via email attachments or downloads for websites. Both of these types of malware have impacted law enforcement, hospitals, governments, and academic institutions and cost millions of dollars to recover. 

Automation
__________

This is a very difficult Sub-Control to automate. Keeping offline backups means that once a backup is created, it needs to be manually removed from the network and stored elsewhere.

Guidance and Tools 
__________________

The following documents can provide additional assistance in defending against ransomware: 

* US-CERT: Ransomware - What It Is and What You Can Do About it 
(https://www.us-cert.gov/sites/default/files/publications/Ransomware_Executive_One-Pager_and_Technical_Document-FINAL.pdf).
* National Cyber Security Centre of the United Kingdom (UK): Mitigating Malware
(https://www.ncsc.gov.uk/guidance/mitigating-malware).
* NIST National Cybersecurity Center of Excellence (NCCoE): Data Integrity
(https://www.nccoe.nist.gov/sites/default/files/library/sp1800/di-nist-sp1800-11-draft.pdf).

*Step-by-step instructions for implementing this Sub-Control can be found in*: Creating System Images with Windows 10 Pro.  
