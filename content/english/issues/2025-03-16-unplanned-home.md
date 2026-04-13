---
title: Unplanned storage outage on Grex 
date: 2025-03-16 10:00:00
resolved: true
resolvedWhen: 2025-03-16 17:10:00
severity: down
affected:
  - NFS /home
section: issue
---

#### The filesystem came back ####

As of now, it is working. We will investigate the cause and update the notice. If you see any problem with your data on /home , please do not hesitate to contact us at support@tech.alliancecan.ca , mentioning Grex in the subject line.

#### Failure of the NFS /home filesystem ####

The NFS storage had failed around 10AM Sunday, March 16. The /home filesystem is currently unavailable.
Jobs, even those that are running from the /project filesystem, may lack access to the local software stack.
Thus we have placed a SLURM reservation to prefent new jobs from starting.

We are working on resolving the issue. Thank you for your patience!

