```
Usage:
fs tier [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    Show object storage connectivity for each node in the cluster

Subcommands:
   location   Show data storage location for a given path
   fetch      Fetch object-stored files to SSD storage
   s3         List S3 object storage configuration and status

Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
