# Synopsis

```weka cluster host memory <host-id> <memory> [--HOST HOST] [--PORT PORT] [--json] [--raw-units] [--UTC]```

# Description

Dedicate host's RAM to weka

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | Host ID as shown in `weka cluster host` |
| `memory` | Memory dedicated to weka in bytes, set to 0 to set this value automatically (format: capacity in decimal or binary units: 11B, 1KB, 1MB, 1GB, 1TB, 1PB, 1EB, 1ZB, 1YB, 1KiB, 1MiB, 1GiB, 1TiB, 1PiB, 1EiB, 1ZiB, 1YiB) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
