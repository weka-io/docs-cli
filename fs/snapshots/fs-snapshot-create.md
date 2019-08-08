# Synopsis

```weka fs snapshot create <file-system>
                        <name>
                        [--access-point access-point]
                        [--source-snapshot source-snapshot]
                        [--HOST HOST]
                        [--PORT PORT]
                        [--is-writable]
                        [--json]
                        [--raw-units]
                        [--UTC]```

# Description

Create a snapshot

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `file-system` | Source Filesystem name |
| `name` | Target Snapshot name |
| `--access-point` | Access point |
| `--source-snapshot` | Source snapshot |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--is-writable` | Writable |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
