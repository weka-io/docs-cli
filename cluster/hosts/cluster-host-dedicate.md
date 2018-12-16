# Synopsis

```weka cluster host dedicate <host-id> <on> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]```

# Description

Set the host as dedicated to weka. For example it can be rebooted whenever needed, and configured by weka for optimal performance and stability

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | Host ID as shown in `weka cluster host` |
| `on` | Set the host as weka dedicated, off unsets host as weka dedicated |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
