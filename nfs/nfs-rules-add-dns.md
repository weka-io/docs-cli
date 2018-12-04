```
Usage:
nfs rules add dns <name> <dns> [--ip ip] [--HOST HOST] [--PORT PORT] [--json]

Description:
    Add a DNS rule to an NFS client group

Arguments:
   name   Group name
   dns    DNS rule with *?[] wildcards rule
Options:
   --ip         IP with netmask rule, in the 1.1.1.1/255.255.0.0 format
   -H, --HOST   Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT   Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json   Format output as JSON
```
