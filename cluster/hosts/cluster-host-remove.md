```
Usage:
cluster host remove <host-id> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    Remove a host from the cluster

Arguments:
   host-id   The host ID of the host to be removed
Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
