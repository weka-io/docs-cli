```
Usage:
smb user add <username> <password> [--uid uid] [--gid gid] [--HOST HOST] [--PORT PORT] [--json]

Description:
    Add a new user that can login to samba

Arguments:
   username   The name of the user to add
   password   The password to set for the user
Options:
   --uid        The uid to give to the user
   --gid        The gid to give to the user
   -H, --HOST   Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT   Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json   Format output as JSON
```
