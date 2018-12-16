# Synopsis

```weka fs snapshot delete <file-system> <name> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]```

# Description

Delete a snapshot

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `file-system` | Source Filesystem name |
| `name` | Snapshot name |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
