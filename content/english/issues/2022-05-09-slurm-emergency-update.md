---
title: Emergency SLURM update wiped all running jobs
date: 2022-05-09 00:00:00
resolved: true
resolvedWhen: 2022-05-09 11:00:00
severity: down
affected:
  - Compute nodes
section: issue
---

## SLURM security update

SLURM scheduler's authors announced a severe security vulnerability, and dropped old SLURM versions from support at the same time. 
This forced us to upgrade SLURM version 19 we used to run, to the supported version 21, immediately.
Unfortunately, the SLURM state got corrupted during the update, and all running jobs were lost. We apologize for the inconvenience. 

The system is expected to run normally with the new SLURM. If you notice any anomalies, please contact us at support@computecanada.ca , mentioning Grex in the subject line.
