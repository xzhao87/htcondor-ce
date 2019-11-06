HTCondor-CE [![Build Status](https://travis-ci.org/htcondor/htcondor-ce.svg?branch=v3)](https://travis-ci.org/htcondor/htcondor-ce)
===========

A site grid gatekeeper technology based solely on HTCondor components.

This package is simply a thin set of wrappers around HTCondor, allowing you to
run a HTCondor-CE without disrupting a site HTCondor install.

For example, `condor_ce_q` is the HTCondor-CE equivalent to `condor_q` for the
HTCondor-CE processes.  This package took much of its inspiration - and base 
code - from OSGs condor-cron package.

Sites are encouraged to install the sub-package `htcondor-ce-condor` or
`htcondor-ce-pbs`, depending on which batch manager they run.

Download
--------

HTCondor-CE RPMs are available from the following locations:

- HTCondor Yum repositories: https://research.cs.wisc.edu/htcondor/yum/
- OSG Yum repositories: https://opensciencegrid.org/docs/common/yum/

Versioning
----------

HTCondor-CE follows the same stable/development release series model as [HTCondor](https://htcondor.readthedocs.io/en/latest/version-history/introduction-version-history.html).
The `master` branch contains the latest version of HTCondor-CE (i.e. development) while the `stable` branch contains the
previous version.
As of September 2019, we maintain two different versions of HTCondor-CE:

- [master](https://github.com/htcondor/htcondor-ce/tree/master): HTCondor-CE 4 ([documentation](https://htcondor-ce.readthedocs.io/en/latest/))
- [stable](https://github.com/htcondor/htcondor-ce/tree/stable): HTCondor-CE 3 ([documentation](https://htcondor-ce.readthedocs.io/en/stable/))
