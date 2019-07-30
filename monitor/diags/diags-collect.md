# Synopsis

```weka diags collect [--id id]
                   [--timeout timeout]
                   [--output-dir output-dir]
                   [--core-limit core-limit]
                   [--HOST HOST]
                   [--PORT PORT]
                   [--clients]
                   [--tar]
                   [--verbose]
                   [--raw-units]
                   [--UTC]```

# Description

Collect diags from all cluster hosts to a directory on the host running this command

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-i, --id` | Optional ID for this dump, if not specified a random ID is generated |
| `-T, --timeout` | How long to wait when downloading diags from all hosts. Default is 10 minutes, 0 means indefinite (format: 3s, 2h, 4m, 1d, 1d5h, 1w) |
| `-d, --output-dir` | Directory to save the diags dump to, default: /opt/weka/diags |
| `-c, --core-limit` | Limit to processing this number of core dumps, if found (default: 1) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--clients` | Collect diags from clients as well as backends (by default diags are only collected from backends) |
| `-t, --tar` | Create a TAR of all collected diags |
| `-v, --verbose` | Print results of all diags, including successful ones |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
