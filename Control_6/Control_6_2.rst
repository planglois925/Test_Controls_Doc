Control 6.2: Activate Audit Logging
=========================================

Ensure that local logging has been enabled on all systems and networking devices. 

Category
________
Technical 

Purpose
_______
On the surface, logging may appear to be a low priority activity, but it is a critical cybersecurity control to have in place within an enterprise. Once a security breach occurs, reviewing logs is often the primary way that computer incident responders identify who did what, and when they did it. Furthermore, if logging is enabled on network devices (e.g., routers), historical activities can be tracked for the entire enterprise network. Logs can also be helpful to an enterprise when performing general maintenance activities to understand the current status of computer systems and networks, and be notified to take action if there is a problem. 

Logging is not a prevention mechanism, meaning that logs do not stop any attacks directly. Instead logs help to provide tamper detection, which means if an unauthorized modification occurs within an enterprise computer system (or its data), it is possible to know that something was changed.

Automation
__________
There are various methods of how to automate logging. Enabling logging on systems can be done manually on a system by system basis. Yet logging is often considered a system configuration option and can be automated with software dedicated to assessing and implementing secure configurations. Moving past just enabling logs, systems known as SIEMs (security information and event management) can be utilized that ingest log data from all systems in an enterprise, and perform data analysis to find breaches or network-wide issues or failures. SEIMs typically require a more advanced IT infrastructure and dedicated IT personnel to manage. 

Guidance and Tools 
__________________
There are many types of logs that can be enabled. When beginning to enable logging on enterprise systems, utilize software and hardware inventory lists to ensure that the proper types of logs were enabled for each system or application. Look to enable logs for both the operating systems and supported applications for all enterprise systems, and also survey network devices like firewalls and wireless access points to understand their logging capabilities. In order to enable logging on firewalls and wireless access points, documentation may be required for the unique network appliance in an enterprise.

.. image:: _static/BenchmarksLogo.png

CIS offers free PDFs with configuration guidelines for 100+ technologies (https://www.cisecurity.org/cis-benchmarks).

*Step-by-step instructions for implementing this Sub-Control can be found in*: Enabling the System Event Audit Log for Windows 10 Pro.


