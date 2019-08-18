# Synopsis

```weka user login <username> <password> [--org org] [--HOST HOST] [--PORT PORT]```

# Description

Logs a user into the Weka cluster. If login is successful, the user credentials are saved to the user homedir.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `username` | User's username |
| `password` | User's password |
| `--org` | Organization name or ID |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
