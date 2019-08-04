# Synopsis

```weka cluster hot-spare [--HOST HOST]
                       [--PORT PORT]
                       [--skip-resource-validation]
                       [--json]
                       [--raw-units]
                       [--UTC]
                       [<count>]...```

# Description

Get or set the number of hot-spare failure-domains in the cluster. If <count> param is not given, the current number of hot-spare FDs will be listed

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `count` | The number of failure-domains |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--skip-resource-validation` | Skip verifying that the cluster has enough RAM and SSD resources allocated for the hot-spare |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
