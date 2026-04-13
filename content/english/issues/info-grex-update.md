---
title: Grex update outage, New Status webpage
date: 2021-07-28 18:05:00
informational: true
section: issue
---

## NOTICE: Grex is online for production.

After the last outage, Grex was in production in a test mode for a week since
June 9, 2021. We did not get any reports about the new hardware and software.
Everything worked as expected. The /home was already migrated to a new, 
NVME-based server.

Now, all users are encouraged to submit their jobs as usual. To see the time
limit and other characteristics of all partitions, you can use our custom
script “partition-list”

To submit a job, you need to specify which partition to use by adding to your
job script “#SBATCH --partition=<partition-name>” where partition-name is one
of the following: compute, skylake, largemem . Note that bigmem partition 
was eliminated (merged into compute). 

If you have questions or concerns, please don’t hesitate to contact us at:
  support@computecanada.ca , mentioning Grex in the subject line.
  
## New status website

Grex has now a new Status website! Visit https://grex-status.netlify.app !
