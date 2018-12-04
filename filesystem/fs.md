```
Usage:
fs [--name name] [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    List filesystems defined in this Weka cluster

Subcommands:
   create     Create a filesystem
   download   Download a filesystem from object store
   update     Update a filesystem
   delete     Delete a filesystem
   restore    Restore filesystem content from a snapshot
   group      List filesystem groups
   snapshot   List snapshots
   tier       Show object storage connectivity for each node in the cluster

Options:
   --name           Filesystem name
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
