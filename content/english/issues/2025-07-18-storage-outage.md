---
title: Unplanned project storage outage in HPCC
date: 2025-07-18 07:10:00
resolved: true
resolvedWhen: 2025-07-18 17:30:00
severity: disrupted
affected:
  - Lustre /project
section: issue
---

#### Update 17:30 Central Time: System is available ####

The storage is working. If you notice any issues with the storage, please do not hesitate to contact us at support@tech.alliancecan.ca, mentioning Grex in the subject line. 

#### Update 17:00 Central Time: System is available with conditions ####

The failure was traced to a hardware issue on one of the storage controllers. 
We have cleared the controller state and restarted the /project storage appliance.
However, the storage targets are not yet properly balanced across the storage servers, so there can be some performance issues. We are working with the storage vendor to address these issues.

As of now, OpenOnDemand and /project are now available, and Grex system would accept new jobs. 

#### A /project storage outage happened on Grex ####

A /project storage outage happened on Grex this morning! The /project filesystem became unavailable.
This affectes running jobs and access to the OpenOnDemand portal as well. We are investigating the issue.
