Control 13.6: Encrypt Mobile Device Data 
==============================================================

Utilize approved cryptographic mechanisms to protect enterprise data stored on all mobile devices

.. note::

	The definition of a *mobile device* varies from organization to organization. Some organizations will only apply this Sub-Control to smartphones and tablets, whereas others will include laptops within the purview of "mobile." Organizations defining laptops as mobile devices should look to ensure that BitLocker is implemented. 

Category
________
Technical

Purpose
_______
Smartphones and tablets used by employees for work activities contain a treasure trove of sensitive enterprise data. This includes both personal devices and those provided by the company. This is true for upper management, rank and file, and all employees in between. It is commonplace for employees to use a phone to obtain company email. Therefore, an organization’s sensitive email, with proprietary secrets, financials, and more, is stored on a device that an employee could easily misplace or have stolen. One of the best ways to help protect against these failures is to encrypt a company’s information while on the device. 

Automation
__________
This Sub-Control is automatable if the correct combination of hardware, software, and policy is purchased. The correct software to obtain will depend on the way that enterprise devices are provided to employees such as with Bring Your Own Device (BYOD) scenarios. Enterprise mobility management (EMM) systems can force all of the smartphones or tablets accessing company email to encrypt mobile data. This Sub-Control can also be solved in a manual fashion with the correct configuration options without much effort. 

Guidance and Tools 
__________________
Mobile data is often secured by default on mobile devices, but this is not always the case. For each phone accessing enterprise email, the appropriate encryption setting must be selected. This will look different on each type of phone, so it may be difficult to identify step-by-step instructions. A vast majority of users will have phones from Samsung, Google, or Apple, therefore identifying and learning how to encrypt data on each of these platforms will often be sufficient. For additional information on how to secure mobile devices, reference the CIS Mobile Companion Guide. It was created with many of the industry’s leading experts and provides created detailed guidance for how to secure mobile devices. 

.. image:: _static/BenchmarksLogo.png

CIS provides detailed instructions for how to secure Google’s Android and Apple’s iOS mobile platforms. Instructions for encrypting the device can be found within these two documents (https://www.cisecurity.org/benchmark/google_android),(https://www.cisecurity.org/benchmark/apple_ios). 
