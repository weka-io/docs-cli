# Synopsis

```weka cluster host add <hostname> [--ip ip] [--HOST HOST] [--PORT PORT] [--no-wait] [--json] [--raw-units] [--UTC]```

# Description

Add a host to the cluster

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `hostname` | Management network hostname |
| `--ip` | Management IP; If empty, the hostname is resolved; If host is highly-available, use IP pairs '<ip>+<ip>'; |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--no-wait` |  |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
