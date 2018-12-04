```
Usage:
user passwd <username> <password> [--HOST HOST] [--PORT PORT] [--json]

Description:
    Set a user's password. If the currently logged-in user is an admin, it can change the password for all other users
    in the Weka cluster.

Arguments:
   username   User's name
   password   User's password
Options:
   -H, --HOST   Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT   Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json   Format output as JSON
```
