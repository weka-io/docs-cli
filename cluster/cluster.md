```
Usage:
cluster 

Description:
    Commands that manage the cluster

Subcommands:
   create           Form a Weka cluster from hosts that just has Weka installed on them
   update           Update cluster configuration
   nodes            List the cluster nodes
   failure-domain   List the Weka cluster failure domains
   hot-spare        Get or set the number of hot-spare failure-domains in the cluster. If <count> param is not given,
                    the current number of hot-spare FDs will be listed
   start-io         Start IO services
   stop-io          Stop IO services
   drive            List the cluster's drives
   host             List the cluster hosts
   default-net      List the default data networking configuration
   license          Get information about the current license status, how much resources are being used in the cluster
                    and whether or not your current license is valid.

```
