---
title: Planned Grex outage for HPCC work and storage update
date: 2023-02-22 14:30:00
resolved: True
resolvedWhen: 2023-02-27 3:00:00
severity: down
affected:
  - Login nodes
  - Compute Nodes
  - Lustre /global/scratch
section: issue
---

#### UPDATE: outage concluded ####

  During the outage of Feb 22, few changes have been made on Grex:
We reinstalled all login and compute nodes with a new image to fix the errors with UCX.
We have added a new storage “project” with similar structure as for Compute Canada.
All the data from scratch has been moved to the project file system.

For an overview of the  changes, please have a look to the documentation page:

https://um-grex.github.io/grex-docs/docs/lustre/


#### Planned Grex outage ####
The Grex storage outage is about to start. Please save your interactive work! ETA for the outage's end is Feb 23 or Friday, Feb 24, 2023.

During the outage we are planning to reboot and reinstall all of Grex compute and login nodes, connect the new Project storage, and perform some re-cabling of the Infiniband fabric of the cluster.
Jobs that are still running by the time of the outage will be lost, and Grex login nodes will be unavailable during the outage window.

Thank you for your patience! If you have questions or concerns regarding the outage, please do not hesitate to contact us at  <mailto:support@tech.alliancecan.ca> !

