# Synopsis

```weka cluster drive add <host-id> [--HOST HOST] [--PORT PORT] [--force] [--json] [--NO-HUMAN] [<device-paths>]...```

# Description

Add the given drive

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | The host the drive attached to (given by ids) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--force` |  |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
