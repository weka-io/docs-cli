```
Usage:
user [--HOST HOST] [--PORT PORT] [--json]

Description:
    List users defined in the Weka cluster

Subcommands:
   login    Logs a user into the Weka cluster. If login is successful, the user credentials are saved to
            ~/.weka/cli.conf
   whoami   Get information about currently logged-in user
   passwd   Set a user's password. If the currently logged-in user is an admin, it can change the password for all
            other users in the Weka cluster.
   add      Create a new user in the Weka cluster
   delete   Delete user from the Weka cluster

Options:
   -H, --HOST   Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT   Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json   Format output as JSON
```
