```
Usage:
cluster host net remove <name> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    Undedicate a networking device in a host.

Arguments:
   name   Net device name, e.g. host0net0
Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
