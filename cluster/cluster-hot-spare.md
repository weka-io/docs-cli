```
Usage:
cluster hot-spare [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN] [<count>]...

Description:
    Get or set the number of hot-spare failure-domains in the cluster. If <count> param is not given, the current
    number of hot-spare FDs will be listed

Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
