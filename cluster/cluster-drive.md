```
Usage:
cluster drive [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    List the cluster's drives

Subcommands:
   scan         Scan for provisioned drives on the cluster's hosts
   activate     Activate the supplied drive, or all drives (if none supplied)
   deactivate   Deactivate the supplied drive(s)
   add          Add the given drive

Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
