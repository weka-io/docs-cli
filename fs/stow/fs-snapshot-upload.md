# Synopsis

```weka fs snapshot upload <file-system> <snapshot> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]```

# Description

Upload a snapshot to object store

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `file-system` | Filesystem name |
| `snapshot` | Snapshot name |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
