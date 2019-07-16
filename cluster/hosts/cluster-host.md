# Synopsis

```weka cluster host [--HOST HOST]
                  [--PORT PORT]
                  [--backends]
                  [--clients]
                  [--leadership]
                  [--leader]
                  [--json]
                  [--raw-units]
                  [--UTC]
                  [<host-ids>]...```

# Description

List the cluster hosts

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-ids` | Only return these host IDs. |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-b, --backends` | Only return backend hosts |
| `-c, --clients` | Only return client hosts |
| `-l, --leadership` | Only return hosts that are part of the cluster leadership |
| `-L, --leader` | Only return the cluster leader |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
