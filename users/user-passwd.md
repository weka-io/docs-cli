# Synopsis

```weka user passwd <username> <password> [--HOST HOST] [--PORT PORT] [--json]```

# Description

Set a user's password. If the currently logged-in user is an admin, it can change the password for all other users in the Weka cluster.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>username</pre> | User's name |
| <pre>password</pre> | User's password |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
