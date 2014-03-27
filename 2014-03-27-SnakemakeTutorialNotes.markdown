---
title :  Notes from Sean Davis' presentation on Snakemake
categories : [notes]
---

- swarm scripts
* difficult to run new data through same pipeline (ends up re-running things)
* changing pipelines also difficult

- how does reproducibility impact our work?

- In R - BatchJobs (http://cran.r-project.org/web/packages/BatchJobs/index.html)

- temp files - really keeps things until they are not needed by any other step
- protected files - prevent overwriting, deleting!!!

- `localrules` run where master process is

- can import R and run (and substitute python vars)
