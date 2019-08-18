# Synopsis

```weka user change-role <username> <role> [--HOST HOST] [--PORT PORT] [--json]```

# Description

Change the role of an existing user.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `username` | Username of user to change the role of |
| `role` | New role to set for the user (format: 'regular', 'readonly', 'orgadmin' or 'clusteradmin') |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
