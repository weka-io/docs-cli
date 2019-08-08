# Synopsis

```weka nfs interface-group ip-range add <name> <ips> [--HOST HOST] [--PORT PORT] [--json]```

# Description

Add an ip range to an interface group

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | Interface group name |
| `ips` | IP range (format: A.B.C.D-E, e.g. 1.2.3.4-8) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
