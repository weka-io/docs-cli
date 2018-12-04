```
Usage:
fs snapshot create <file-system>
                   <name>
                   <access-point>
                   [--source-snapshot source-snapshot]
                   [--HOST HOST]
                   [--PORT PORT]
                   [--is-writable]
                   [--json]
                   [--NO-HUMAN]

Description:
    Create a snapshot

Arguments:
   file-system    Source Filesystem name
   name           Target Snapshot name
   access-point   Access point
Options:
   --source-snapshot   Source snapshot
   -H, --HOST          Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT          Specify the port. Alternatively, use the WEKA_PORT env variable
   --is-writable       Writable
   -J, --json          Format output as JSON
   -N, --NO-HUMAN      Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                       2GiB.
```
