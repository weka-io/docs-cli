# Synopsis

```weka cluster host deactivate [--HOST HOST]
                             [--PORT PORT]
                             [--no-wait]
                             [--skip-resource-validation]
                             [--json]
                             [--raw-units]
                             [--UTC]
                             [<host-ids>]...```

# Description

Deactivate the supplied host(s)

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--no-wait` |  |
| `--skip-resource-validation` | Skip verifying that the cluster will still have enough RAM and SSD resources after deactivating the hosts |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
