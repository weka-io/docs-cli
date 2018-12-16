# Synopsis

```weka cluster host bandwidth <host-id> <bandwidth> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]```

# Description

Limit weka's bandwidth on the host

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | Host ID as shown in `weka cluster host` |
| `bandwidth` | Bandwith to limmit |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
