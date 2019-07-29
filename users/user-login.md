# Synopsis

```weka user login <username> <password> [--tenant tenant] [--HOST HOST] [--PORT PORT]```

# Description

Logs a user into the Weka cluster. If login is successful, the user credentials are saved to ~/.weka/cli.json

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `username` | User's name |
| `password` | User's password |
| `--tenant` | Tenant name or ID |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
