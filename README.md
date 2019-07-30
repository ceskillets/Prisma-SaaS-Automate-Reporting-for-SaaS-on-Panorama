# ShadowIT_Report_Panorama

Scheduled SaaS Application Usage Report From Panorama- 
The purpose of this Skillet is to automate the creation of a scheduled SaaS Application Usage Report on Panorama.

In order to get the most from this skillet and the report it creates, it is highly recommended that SSL Decryption be used, and all or as many security rules as possible have profiles attached configured to log as verbosely as possibly (preferably logging all).

The skillet will perform the following tasks:

Create 3 detailed SaaS Application Usage Reports under the Monitor tab - SaaS Application Usage Report for trailing 7, 30, and 90 days.
Create an Email Server Profile under the Settings - Email Server page. This will require a mail server which is configured to allow the NGFW or Panorama to relay mail, please see the PAN-OS Admin Guide for additional details on mail server setup requirements.
Create an automated scheduler which will email the selected report on a weekly schedule on Sunday so that administrators can review when arriving at work on Monday morning.

Support Policy
The code and templates in the repo are released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.

