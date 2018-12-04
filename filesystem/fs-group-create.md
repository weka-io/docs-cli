```
Usage:
fs group create <name> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    Create a filesystem group (non-tiered)

Arguments:
   name   The filesystem group name to be created
Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
