# Synopsis

```weka cluster default-net set [--range range]
                             [--gateway gateway]
                             [--netmask-bits netmask-bits]
                             [--HOST HOST]
                             [--PORT PORT]
                             [--json]
                             [--NO-HUMAN]```

# Description

Set the default data networking configuration

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--range` | IP range in the form of '1.2.3.4-8' |
| `--gateway` | Default gateway IP |
| `--netmask-bits` | Subnet mask bits (0..32) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
