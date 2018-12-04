```
Usage:
cluster license [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    Get information about the current license status, how much resources are being used in the cluster and whether or
    not your current license is valid.

Subcommands:
   payg    Enable pay-as-you-go for the cluster
   reset   Removes existing license information, returning the cluster to an unlicensed mode
   set     Set the cluster license

Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
