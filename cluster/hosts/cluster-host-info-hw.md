# Synopsis

```weka cluster host info-hw [--HOST HOST] [--PORT PORT] [--info-type info-type]... [--json] [--NO-HUMAN] [<hostnames>]...```

# Description

Show hardware information about one or more hosts

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--info-type` | Specify what information to query: version&#124;osinfo&#124;memory&#124;cores&#124;disks&#124;eths&#124;net&#124;ips |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
