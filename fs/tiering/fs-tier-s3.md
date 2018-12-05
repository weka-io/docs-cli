```
Usage:
fs tier s3 [--name name] [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    List S3 object storage configuration and status

Subcommands:
   add      Create a new S3 object storage connection
   update   Edit an existing S3 object storage connection
   delete   Delete an existing S3 object storage connection

Options:
   --name           Name of the Object Storage
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
