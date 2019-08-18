# Synopsis

```weka cluster host remove <host-id> [--HOST HOST] [--PORT PORT] [--json] [--raw-units] [--UTC]```

# Description

Remove a host from the cluster

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | The host ID of the host to be removed |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
