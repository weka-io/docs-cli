# Synopsis

```weka nfs interface-group add <name> <type> [--subnet subnet] [--gateway gateway] [--HOST HOST] [--PORT PORT] [--json]```

# Description

Create an interface group

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | Interface group name |
| `type` | Group type. cli subnet type can be NFS |
| `--subnet` | subnet mask in the 255.255.0.0 format |
| `--gateway` | gateway ip |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
