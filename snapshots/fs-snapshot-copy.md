```
Usage:
fs snapshot copy <file-system> <source-name> <destination-name> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    Copy one snapshot over another

Arguments:
   file-system        Source Filesystem name
   source-name        Source snapshot name
   destination-name   Destination snapshot name
Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
