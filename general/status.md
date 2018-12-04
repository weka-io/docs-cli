```
Usage:
status [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]

Description:
    Get an overall status of the Weka cluster

Subcommands:
   rebuild   Show the cluster phasing in/out progress, and protection per fault-level

Options:
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
