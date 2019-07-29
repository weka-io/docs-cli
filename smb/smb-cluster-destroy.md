# Synopsis

```weka smb cluster destroy [--HOST HOST] [--PORT PORT] [--force] [--json]```

# Description

Destroy the SMB cluster managed by weka. This will not delete the data, just stop exposing it via SMB

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-f, --force` | Force this action without further confirmation (this command may disrupt IO service for connected SMB clients and can be undone by re-creating the SMB cluster) |
| `-J, --json` | Format output as JSON |
