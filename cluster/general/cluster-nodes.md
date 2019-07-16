# Synopsis

```weka cluster nodes [--HOST HOST] [--PORT PORT] [--host host]... [--json] [--raw-units] [--UTC] [<node-ids>]...```

# Description

List the cluster nodes

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `node-ids` | Only return these node IDs. |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--host` | Only return the nodes of these host IDs, if not specified the nodes for all the hosts will be returned |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
