# Synopsis

```weka nfs interface-group port delete <name> <host-id> <port> [--HOST HOST] [--PORT PORT] [--force] [--json]```

# Description

Delete a host port from an interface group

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | Interface group name |
| `host-id` | Host ID on which the port resides |
| `port` | Port's device. (e.g. eth1) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-f, --force` | Force this action without further confirmation (this command may disrupt IO service for connected NFS clients and can be undone by re-adding the port) |
| `-J, --json` | Format output as JSON |
