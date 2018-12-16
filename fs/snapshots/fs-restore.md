# Synopsis

```weka fs restore <file-system> <source-name> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]```

# Description

Restore filesystem content from a snapshot

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `file-system` | The name of the Filesystem to be restored |
| `source-name` | The name of the source snapshot |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
