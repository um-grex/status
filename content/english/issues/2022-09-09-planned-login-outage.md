---
title: Planned Network outage of the login nodes
date: 2022-09-09 11:45:00
resolved: True
resolvedWhen: 2022-08-14 12:00:00
severity: disrupted
affected:
  - Login nodes
  - Network
section: issue
---

# Update: the switch complete!

Grex's internet connection to all login nodes is now migrated to the UManitoba network IP space. New login node names:

grex.hpc.umanitoba.ca (instead of grex.westgrid.ca; same for the ones below)
bison.hpc.umanitoba.ca
tatanka.hpc.umanitoba.ca
yak.hpc.umanitoba.ca 
aurochs.hpc.umanitoba.ca

# SWITCHING GREX NETWORK FROM BCNET TO UMANITOBA NETWORK. <==

  On Friday, Sep 09 between 12:00 and 2:00 PM, we will switch the network
  from BCNET {westgrid.ca} to UManitoba network. During this process, access
  to Grex via old DNS names {grex, bison, tatanka} will be disrupted. We expect
  less disruption for yak.hpc.umanitoba.ca

  The process will not affect users' data.

  OpenOnDemand interface will also be disabled and hopefully the service will
  be restored sometime after the outage when new SSL certificates are in place.

  In the meantime, you can use yak to connect to Grex:

  ssh your-user-name@yak.hpc.umanitoba.ca

  Replace <your-user-name> by your Alliance (Compute Canada) user name.

  Please note that this node has avx512 architecture and if you have to use it
  for compiling your codes, they may not run on “compute” partition. Other than
  that, it should behave as any other old login node.
