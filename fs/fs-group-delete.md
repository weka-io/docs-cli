# Synopsis

```weka fs group delete <name> [--HOST HOST] [--PORT PORT] [--json] [--raw-units] [--UTC]```

# Description

Delete a filesystem group

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | The name of the filesystem group to be deleted |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
