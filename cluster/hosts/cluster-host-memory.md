# Synopsis

```weka cluster host memory <host-id> <memory> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]```

# Description

Dedicate host's RAM to weka

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | Host ID as shown in `weka cluster host` |
| `memory` | Memory dedicated to weka in bytes. Set to 0 to let weka decide. |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
