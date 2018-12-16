# Synopsis

```weka nfs interface-group assignment [--name name] [--HOST HOST] [--PORT PORT] [--json]```

# Description

List the currently assigned interface for each floating-IP address in the given interface-group. If <name> is not supplied, assignments for all floating-IP addresses will be listed

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--name` | Group name |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
