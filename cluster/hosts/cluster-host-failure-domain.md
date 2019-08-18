# Synopsis

```weka cluster host failure-domain <host-id>
                                 [--name name]
                                 [--HOST HOST]
                                 [--PORT PORT]
                                 [--auto]
                                 [--per-drive]
                                 [--json]
                                 [--raw-units]
                                 [--UTC]```

# Description

Set the host failure-domain

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | Host ID as shown in `weka cluster host` |
| `--name` | Add this host to a named failure-domain. A failure-domain will be created if it doesn't exist yet. |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--auto` | Set this host to be a failure-domain of its own |
| `--per-drive` | Place each drive in its own failure-domain, cancelling the host failure-domain |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
