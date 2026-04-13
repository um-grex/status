---
title: Planned power outage Aug 31 to Sept 1
date: 2021-08-31 08:00:00
resolved: true
resolvedWhen: 2021-09-01 12:00:00
severity: down
affected:
  - Compute nodes
  - Login nodes
  - NFS /home
  - Lustre /global/scratch
section: issue
---

## Grex is back online

Grex is back online, accepting CPU jobs. GPU nodes will take a bit more to reinstall NVIDIA updates, but will be online by end of today.

The previous jobs on the queue were lost since the outage afftected all 
compute nodes that are rebooted after restoring the power. Please check 
your data and re-submit the jobs that are not done before the outage.

## Grex will be down for a campus power maintenance

Physical Plant has a planning a power outage for power breakers maintenance. This will affect Grex building, so and all the nodes and strage systems will be shut-down. The system will be unavailable for users, and all running jobs will be lost. We will be performing some work on Grex during the maintenance window as well. ETA for Grex availabinity is noon, September 1. 

If you have questions or concerns, please don’t hesitate to contact us at: support@computecanada.ca , mentioning Grex in the subject line.
