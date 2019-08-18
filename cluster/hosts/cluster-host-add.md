# Synopsis

```weka cluster host add <hostname>
                      [--ip ip]
                      [--auto-remove-timeout auto-remove-timeout]
                      [--HOST HOST]
                      [--PORT PORT]
                      [--no-wait]
                      [--json]
                      [--raw-units]
                      [--UTC]```

# Description

Add a host to the cluster

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `hostname` | Management network hostname |
| `--ip` | Management IP. If empty, the hostname is resolved. |
| `--auto-remove-timeout` | How long to wait (in seconds) before removing this host if it disconnects from the cluster. Minimum value is 60, use 0 to disable automatic removal (default). Only Available for clients. |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--no-wait` |  |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
