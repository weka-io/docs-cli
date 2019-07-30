# Synopsis

```weka cluster drive [--HOST HOST] [--PORT PORT] [--json] [--raw-units] [--UTC] [<uuids>]...```

# Description

List the cluster's drives

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `uuids` | A list of drive IDs or UUIDs to list. If no ID is supplied, all drives are listed. |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
