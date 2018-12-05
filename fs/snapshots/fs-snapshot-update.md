```
Usage:
fs snapshot update <file-system>
                   <name>
                   [--new-name new-name]
                   [--access-point access-point]
                   [--HOST HOST]
                   [--PORT PORT]
                   [--is-writable]
                   [--json]
                   [--NO-HUMAN]

Description:
    Update snapshot parameters

Arguments:
   file-system   Source Filesystem name
   name          Snapshot name
Options:
   --new-name       Updated snapshot name
   --access-point   Access point
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   --is-writable    Writable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
