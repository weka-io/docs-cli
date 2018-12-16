# Synopsis

```weka nfs rules add ip <name> <ip> [--HOST HOST] [--PORT PORT] [--json]```

# Description

Add an IP rule to an NFS client group

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | Group name |
| `ip` | IP with netmask rule, in the 1.1.1.1/255.255.0.0 format |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
