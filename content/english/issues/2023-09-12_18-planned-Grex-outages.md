---
title: Two Planned Grex outages for HPCC transformer work
date: 2023-09-12 18:00:00
resolved: true
resolvedWhen: 2023-09-19 21:00:00
severity: down
affected:
  - Login nodes
  - Compute Nodes
  - Lustre /global/scratch
  - NFS /home
  - Network
section: issue
---

#### Both power outages are now complete ####

Grex system is open to the users. Queued jobs were not affected and seems to be running now.
There were no major upgrades or changes done during the outage.

#### Planned Grex power outages in September 2023  ####

The Physical Plant is about to perform some electrical works on the transformer that feeds, amongst other things on campus, the HPCC data center that hosts Grex. The outage will start for 6 PM on September 12 and September 19. These outages would require a complete power shutdown in HPCC for about an hour, which means the system would be completely inaccessible to the users, and all running jobs would be terminated.

To avoid the failure of jobs, we have made two reservations to avoid any longer jobs (that cannot be finished before the beginning of the outage) from starting. For more information, run the following command from any login node: "scontrol show res".    To take advantage of the cluster before, and between, the outages, we recommend users submit short jobs that can finish by the time the upcoming outage begins.

Thank you for your patience! Should you have questions or concerns, please do not hesitate to contact us at support@tech.alliancecan.ca !


