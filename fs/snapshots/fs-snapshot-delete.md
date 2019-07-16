# Synopsis

```weka fs snapshot delete <file-system> <name> [--HOST HOST] [--PORT PORT] [--force] [--json] [--raw-units] [--UTC]```

# Description

Delete a snapshot

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `file-system` | Source Filesystem name |
| `name` | Snapshot name |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-f, --force` | Force this action without further confirmation (this command is destructive and cannot be undone) |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
