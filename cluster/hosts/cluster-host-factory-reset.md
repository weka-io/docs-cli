```
Usage:
cluster host factory-reset <guid> [--HOST HOST] [--PORT PORT] [--force] [--json] [--NO-HUMAN] [<hostnames-or-ips>]...

Description:
    Factory resets the hosts. NOTE! this can't be undone!

Arguments:
   guid   The cluster GUID
Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   --force          When set, broute force reset
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
