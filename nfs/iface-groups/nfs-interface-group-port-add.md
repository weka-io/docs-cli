# Synopsis

```weka nfs interface-group port add <name> <host-id> <port> [--HOST HOST] [--PORT PORT] [--json]```

# Description

Add a host's port to an interface group

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | Interface group name |
| `host-id` | Host ID on which the port resides |
| `port` | Port's device. (e.g. eth1) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
