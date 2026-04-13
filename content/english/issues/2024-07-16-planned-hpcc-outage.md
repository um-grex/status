---
title: Planned HPCC/Grex outage for electrical and cooling work.
date: 2024-07-16 6:00:00
resolved: true
resolvedWhen: 2024-07-18 18:00:00
severity: down
affected:
  - Login nodes
  - Compute Nodes
  - Lustre /global/scratch
  - NFS /home
section: issue
---

#### Update 3 on July 18 ####

Cooling in HPCC is working, so the outage is over and Grex is operational. 

#### Update 2 on July 17 ####

Unfortunately, due to heat outside of the datacentre, and the work inside the datacentre, we were unable to keep the environment cool enough to run even the storage and login nodes. So Grex is fully powered down again.

#### Update 1 on July 17 ####

The electrical part of the update is over. We have powered up Grex login nodes and storage, so the users can SSH in and access their data.
What does not yet work is compute, because water cooling is being worked on. So no jobs will get started, and OOD Web portal on zebu is also down.

  * If you have questions or concerns, please don't hesitate to contact us at: 	support@tech.alliancecan.ca

#### Outage started on July 16 ####

There is a planned outage on Grex in effect now. 
During this outage, Physical Plant will work on HPCC power and cooling, and the entire Grex system will be powered down.

Users will not have access to any Grex services (compute and storage and Web portal) during the outage. During the outage, all running jobs will be terminated.

Should you have any questions about the upcoming Grex outage, please do not hesitate to contact us at support@tech.alliancecan.ca ! Thank you for your patience,

Your Grex HPC team.
