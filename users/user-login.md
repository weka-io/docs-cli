# Synopsis

```weka user login <username> <password> [--HOST HOST] [--PORT PORT] [--json]```

# Description

Logs a user into the Weka cluster. If login is successful, the user credentials are saved to ~/.weka/cli.conf

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>username</pre> | User's name |
| <pre>password</pre> | User's password |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
