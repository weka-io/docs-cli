# Synopsis

```weka user login <username> <password> [--HOST HOST] [--PORT PORT]```

# Description

Logs a user into the Weka cluster. If login is successful, the user credentials are saved to ~/.weka/cli.conf

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `username` | User's name |
| `password` | User's password |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
