# Synopsis

```weka fs snapshot update <file-system>
                        <name>
                        [--new-name new-name]
                        [--access-point access-point]
                        [--HOST HOST]
                        [--PORT PORT]
                        [--is-writable]
                        [--json]
                        [--raw-units]
                        [--UTC]```

# Description

Update snapshot parameters

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `file-system` | Source Filesystem name |
| `name` | Snapshot name |
| `--new-name` | Updated snapshot name |
| `--access-point` | Access point |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--is-writable` | Writable |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
