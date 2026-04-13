---
title: Planned Grex outage for Lustre FS and Major Linux update
date: 2024-05-07 9:00:00
resolved: true
resolvedWhen: 2024-05-10 13:00:00
severity: down
affected:
  - Login nodes
  - Compute Nodes
  - Lustre /global/scratch
  - NFS /home
section: issue
---

#### Final update on May 10 ####

The OS and Lustre update outage is over!
   
The OS on Grex was upgraded to Alma Linux on all CPU, GPU and login nodes {except for bison, tatanka and compute partition}. Now, Grex is available for running jobs. Please note the changes about software stack:

>  https://um-grex.github.io/grex-docs/updates/

  * If you have questions or concerns, please don't hesitate to contact us at: 	support@tech.alliancecan.ca

#### Update on May 9 ####

The outage extended into May 10. The /home filesystem had been updated; update of the Linux OS and HPC software is still in progress.
Sorry about the inconvenience and thank you for your patience!

#### Update on May 8 ####

The outage continues. The /project filesystem appliance had been updated.
We are working on updating the /home filesystem, Linux OS and HPC software stacks. The system is still closed for users.

####  Grex system outage on May 7 - 9 2024 ####

There is a planned outage on Grex in effect now . 
We are performing a major update of the DDN Lustre storage controller. We will also do a major Linux OS update from CentOS 7 to AlmaLinux 8.
We will reboot and reinstall all of Grex compute and login nodes. All running and queued jobs will be deleted.
Grex login nodes , compute and storage will be unavailable during the outage window. Thank you for your patience! 
Should you have questions or concerns, please do not hesitate to contact us at support@tech.alliancecan.ca !
