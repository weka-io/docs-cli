# Synopsis

```weka cluster host factory-reset <guid>
                                [--HOST HOST]
                                [--PORT PORT]
                                [--force]
                                [--json]
                                [--raw-units]
                                [--UTC]
                                [<hostnames-or-ips>]...```

# Description

Factory resets the hosts. NOTE! this can't be undone!

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `guid` | The cluster GUID |
| `hostnames-or-ips` | A list of hosts (given by hostname or IP) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--force` | When set, broute force reset |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
