# Synopsis

```weka cluster host auto-remove-timeout <host-id> <auto-remove-timeout> [--HOST HOST] [--PORT PORT] [--json]```

# Description

Set how long to wait before removing this host if it disconnects from the cluster (for clients only)

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | Host ID as shown in `weka cluster host` |
| `auto-remove-timeout` | Minimum value is 60, use 0 to disable automatic removal |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
