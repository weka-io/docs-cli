```
Usage:
smb cluster [--HOST HOST] [--PORT PORT] [--json]

Description:
    View info about the samba cluster managed by weka

Subcommands:
   create    Create a SMB cluster managed by weka
   destroy   Destroy the SMB cluster managed by weka. This will not delete the data, just stop exposing it via SMB

Options:
   -H, --HOST   Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT   Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json   Format output as JSON
```
