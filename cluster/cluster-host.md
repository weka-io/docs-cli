```
Usage:
cluster host [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    List the cluster hosts

Subcommands:
   info-hw          Show hardware information about one or more hosts
   info-config      Show the cluster's current configuration (Hosts, Disks, NICs...)
   failure-domain   Set the host failure-domain
   dedicate         Set the host as dedicated to weka. For example it can be rebooted whenever needed, and configured
                    by weka for optimal performance and stability
   bandwidth        Limit weka's bandwidth on the host
   cores            Dedicate host's cores to weka
   memory           Dedicate host's RAM to weka
   activate         Activate the supplied hosts, or all hosts (if none supplied)
   deactivate       Deactivate the supplied host(s)
   add              Add a host to the cluster
   remove           Remove a host from the cluster
   factory-reset    Factory resets the hosts. NOTE! this can't be undone!
   net              List Weka dedicated networking devices in a host

Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
