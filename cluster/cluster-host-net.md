```
Usage:
cluster host net <host-id> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    List Weka dedicated networking devices in a host

Arguments:
   host-id   The host's id
Subcommands:
   add      Allocate a dedicated networking device on a host (to the cluster).
   remove   Undedicate a networking device in a host.

Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
