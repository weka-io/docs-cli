```
Usage:
cluster host failure-domain <host-id> [--name name] [--HOST HOST] [--PORT PORT] [--auto] [--ha] [--json] [--NO-HUMAN]

Description:
    Set the host failure-domain

Arguments:
   host-id   Host ID as shown in `weka cluster host`
Options:
   --name           Add this host to a named failure-domain. A failure-domain will be created if it doesn't exist yet.
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   --auto           Set this host to be a failure-domain of its own
   --ha             Mark this host as highly available
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
