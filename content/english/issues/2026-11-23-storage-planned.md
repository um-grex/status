---
title: Planned Grex outage - updating DDN Lustre and Home filesystems
date: 2026-11-23 09:00:00
resolved: true
resolvedWhen: 2026-11-24 17:30:00
severity: down
affected:
  - Lustre /project
  - NFS /home
  - Compute nodes
  - Login nodes
  - OpenOnDemand portal
section: issue
---

#### Update: Outage finisged ####

We have updated Lustre software as well as NFS serving /home. We have also performed a minor update of Linux OS and various management software items across Grex. 

Some components are still being working on (most notably Globus endpoint) but in general, Grex is back online, running jobs, and user data is available.

#### A planned Grex  outage Nov 23 ####

We will be performing a planned, full outage of the Grex HPC system, starting at 9:00AM on Monday, November 23, 2026
We expect the outage to last for two days.

We will perform update of the DDN Lustre filesystem appliance, and NFS storage, as well as a minor Linux update on all the compute nodes. 
During the outage, OpenOnDemand, Storage, and Login nodes will not be available.
