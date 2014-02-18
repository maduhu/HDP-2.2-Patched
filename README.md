HDP-2.2-Patched
===============

Hortonworks HDP 2.2.0.2.0.6.0-101 with added patches

Manually added patch from https://issues.apache.org/jira/browse/HDFS-5804 with slight modification.  

Updated user/group nfs cache to always refresh instead of having a timeout.  if a new user is added and then starts interacting with HDFS default nobody userid/group is used.
