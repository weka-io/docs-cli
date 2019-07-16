# Synopsis

```weka nfs client-group delete <name> [--HOST HOST] [--PORT PORT] [--force] [--json]```

# Description

Delete an NFS client group

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | Group name |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-f, --force` | Force this action without further confirmation (this command may disrupt IO service for connected NFS clients and can be undone by re-creating the client group) |
| `-J, --json` | Format output as JSON |
