# Synopsis

```weka smb share remove <share-id> [--HOST HOST] [--PORT PORT] [--force] [--json]```

# Description

Remove a share exposed by samba

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `share-id` | The id of the share to remove |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-f, --force` | Force this action without further confirmation (this command may disrupt IO service for connected SMB clients and can be undone by re-creating the SMB share) |
| `-J, --json` | Format output as JSON |
