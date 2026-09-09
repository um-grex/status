---
title: Planned Grex outage - updating SLURM and home
date: 2026-09-02 08:30:00
resolved: true
resolvedWhen: 2026-09-08 23:10:00
severity: down
affected:
  - Lustre /project
  - NFS /home
  - Compute nodes
  - Login nodes
  - OpenOnDemand portal
section: issue
---

#### Sept 8, outage complete  ####

All the /project migration jobs were completed. Grex is fully available.

#### Status update as of evening of Sept 4  ####

We have to extend the ongoing outage past the planned Sept.4 ending. The tentative ETA is September 8, 2026.
 
 * We have successfully updated Grex’s SLURM scheduler to a current version to address a CVE.
 * We have also migrated all user /home directories to the new storage server. This should be transparent for all users.
 * We are still in the process of migration of /project directories to the new /project filesystem appliance.
 
Due to some issues we have encountered during the storage, our data migration to the new /project filesystem took longer than the expected outage window. Thus we have to extend the Grex outage to September 8.  Some functionality like OpenOnDemand and Nextcloud is not available until the end of the outage.
 
However, we are able to open Grex for SSH access now, to groups whose /project had been migrated, so that they could log in, access their data, run their jobs and thus test the system. Access to Grex is blocked for the groups whose data are still in the process of migration.  As of now, about 95% of all projects were migrated. We apologize for the delay.

#### A planned Grex  outage  ####

We will be performing a planned, full outage of the Grex HPC system, starting at 8:30AM on Tuesday, September 2 2026
We expect the outage to last until end of the day on Friday, September 4. 

We will perform update of the SLURM controller, and NFS storage, as well as a minor Linux update on all the compute nodes. 
During the outage, OpenOnDemand, Storage, and Login nodes will not be available, and all running jobs will be stopped. The outage will not affect the users’ data. 
