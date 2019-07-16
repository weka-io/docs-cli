# Synopsis

```weka cluster default-net set [--range range]
                             [--gateway gateway]
                             [--netmask-bits netmask-bits]
                             [--HOST HOST]
                             [--PORT PORT]
                             [--json]
                             [--raw-units]
                             [--UTC]```

# Description

Set the default data networking configuration

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--range` | IP range (format: A.B.C.D-E, e.g. 1.2.3.4-8) |
| `--gateway` | Default gateway IP |
| `--netmask-bits` | Subnet mask bits (0..32) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
