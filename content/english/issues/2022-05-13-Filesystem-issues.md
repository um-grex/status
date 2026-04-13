---
title: One of the /global/scratch filesystem servers crashed, FS runs in degraded mode
date: 2022-05-13 19:30:00
resolved: true
resolvedWhen: 2022-05-13 22:00:00
severity: disrupted
affected:
  - Lustre /global/scratch
section: issue
---

## Lustre filesystem problems

One of the /global/scratch filesystem servers crashed, FS runs in degraded mode. We are investigating the issue. 
Most running jobs will continiue to run, albeit slower, and may stuck in I/O operations while Lustre servers are unresponsive.

## Update:

After restarting of Lustre servers, the /global/scratch filesystem is back to normal operation.
