# Synopsis

```weka cluster host net <host-id> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]```

# Description

List Weka dedicated networking devices in a host

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | The host's id |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
