# Synopsis

```weka fs tier location <path> [--HOST HOST] [--PORT PORT] [--json] [--raw-units] [--UTC]```

# Description

Show data storage location for a given path

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `path` | Path to get information about |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
