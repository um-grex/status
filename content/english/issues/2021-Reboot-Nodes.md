---
title: Rebooting the nodes
date: 2021-07-27 10:00:00
resolved: true
resolvedWhen: 2021-08-06 13:30:00
severity: notice
affected:
  - Compute nodes , Login nodes
section: issue
---


## Grex nodes will be rebooted and reinstalled to apply a security patch

We started draining the cluster in order to reboot all login and compute nodes to apply security patches. The current running jobs will continue and once finished, the nodes will be rebooted. The pending jobs will wait on the queue till the nodes are rebooted and will start on patched nodes. The process will not affect the data. Only the available resources are limited. 

The operation may take a week or so.

If you have questions or concerns, please don’t hesitate to contact us at: support@computecanada.ca , mentioning Grex in the subject line.
