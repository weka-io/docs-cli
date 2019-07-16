# Synopsis

```weka nfs interface-group ip-range delete <name> <ips> [--HOST HOST] [--PORT PORT] [--force] [--json]```

# Description

Delete an ip range from an interface group

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | Interface group name |
| `ips` | IP range (format: A.B.C.D-E, e.g. 1.2.3.4-8) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-f, --force` | Force this action without further confirmation (this command may disrupt IO service for connected NFS clients and can be undone by re-creating the IP range) |
| `-J, --json` | Format output as JSON |
