Control 10.2: Perform Complete System Backups
==================================================

Ensure that all of the organization’s key systems are backed up as a complete system, through processes such as imaging, to enable the quick recovery of an entire system. 

Category
________
Technical

Purpose
_______
A backup is a duplicate of a computer system’s data, but different types and degrees of backups exist. A backup is commonly viewed as a small collection of a system’s overall data. Often times only a few important folders are backed up, such as containing photos, receipts, contracts, or tax information. This information may be stored on another computer system, external hard drive, removable media, or cloud service. This strategy is insufficient for protecting an organization. Flavors of backups include incremental, differential, or complete. A complete system image is a snapshot of all data and settings on a system.

If a system is breached by an attacker, infected with malware, or involved in an accident (e.g., fire, flood), it often takes a long time to bring a system or network back online. This could include reinstalling and re-configuring all of the enterprise systems and applications. Complete system backups rectify this issue by backing up not just important folders, but by backing up the entire computer, which can be pushed to new systems. Although this approach is a more complex solution, it makes recovery from a disaster or computer incident significantly faster. Backups protect against many types of malware including ransomware and destructive malware. 

Automation
__________
This Sub-Control is entirely automatable, although it requires a medium to advanced level of IT knowledge to initially setup and configure. It is often implemented by configuring a specific application to backup information to an external storage location with sufficient free space. 

Guidance and Tools 
__________________
It is best practice to manually check backups from time to time to make sure that any type of backups that an organization is relying upon is working as intended. Microsoft provides a system image creation and backup utility within Windows 10 Pro. There may be a need to obtain additional tools and services for backing up non-Windows systems. The following are examples of free backup utilities that can be used to take system images:

* EaseUS: This free program can be configured to take system images (https://www.easeus.com/backup-software/tb-free.html).
* Amanda Network Backup: Free, open source backup tool (http://www.amanda.org). 
* Bacula: Open source network backup and recovery solution (http://blog.bacula.org). 

*Step-by-step instructions for implementing this Sub-Control can be found in*: :ref:`Creating System Images with Windows 10 Pro`
