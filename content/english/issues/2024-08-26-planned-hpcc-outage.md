---
title: Planned HPCC/Grex outage for electrical and cooling work.
date: 2024-08-26 8:00:00
resolved: true
resolvedWhen: 2024-09-10 16:00:00
severity: down
affected:
  - Compute nodes
  - Network
  - Lustre /project
section: issue
---

#### Update Sept  10 ####

The outage is over. Grex is fully online and available to users.
There are many important changes made on the Grex system. Please check them out at:

https://um-grex.github.io/grex-docs/updates/ 

Your Grex HPC team.

#### Update Sept  6 ####

Due to a delay with deployment of the new water cooling system, Grex's outage is extended until Wednesday, Sept. 11.
At this point, the cooling for new row of racks cannot be fully enabled. Thus, the partial availability of Grex continues.

  -	SSH to Login nodes (yak.hpc.umanitoba.ca; grex.hpc.umanitoba.ca is now a yak alias)
  -	Home and Project file systems are online.
  -	OpenOnDemand portal (https://zebu.hpc.umanitoba.ca, Simplified Desktop) is online
  - Running jobs of short duration (must end before September 9, 2024) on skylake and GPU partitions would work.

Thank you for your patience!

#### Update Aug 30 ####

We have completed the migration of all of the storage systems, and most of the compute servers into the new datacentre racks. 
However, the cooling system installation and acceptance is due next week, so the Grex system is not yet fully online.

During the long weekend, users have access to the following Grex services or systems:

  -	SSH to Login nodes (yak.hpc.umanitoba.ca; grex.hpc.umanitoba.ca is now a yak alias)
  -	Home and Project file systems are online.
  -	OpenOnDemand portal (https://zebu.hpc.umanitoba.ca, Simplified Desktop) is online
  - Running jobs of short duration (must end before September 3, 2024) on skylake and some of the GPU partitions would work.

The following systems or services are as of now offline and unavailable: Old login nodes tatanka and bison are decommissioned and unavailable.  grex.hpc.umanitoba.ca is now a yak alias. Old compute partition is decommissioned and unavailable. Most new GPU and CPU partitions are offline because the cooling system is yet to be completed in HPCC. 

#### Update as of Aug 28 ####

The First phase: Aug 26 - Aug 28, 2024 is done. We have migrated our storage, login and management nodes to the final location.
Grex is now partially open for users with limitted services:

      - Use the login nodes and OOD portal
      - Access to storage {home and project} if you need to access your data.

Please note that users can not yet submit jobs as the migration of the compute nodes is not done yet, pending completion of the new cooling systems. We may also experience intermittent interruptions with access to the storage and the login nodes as we are continue with the outage.

#### Outage started on Aug 26 ####

There is a planned outage on Grex in effect now. 

During this outage, Physical Plant will work on HPCC power and cooling, and the entire Grex system will be powered down. Then, the system will be migrated to our new water cooled rack infrastructure.

Users will not have access to any Grex services (compute, storage and the OOD Web portal) during the fist stage of the outage that is expected to last at least three days (until Aug 29). 

We will be updating this page as the work in HPCC  progresses. 

Should you have any questions about the upcoming Grex outage, please do not hesitate to contact us at support@tech.alliancecan.ca ! Thank you for your patience,

Your Grex HPC team.
