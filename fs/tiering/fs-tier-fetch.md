# Synopsis

```weka fs tier fetch [--timeout timeout] [--HOST HOST] [--PORT PORT] [--verbose] [--raw-units] [--UTC] [<path>]...```

# Description

Fetch object-stored files to SSD storage

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `path` | A file path to fetch to SSD storage. Multiple paths can be passed, e.g. `find ... &#124; xargs -P32 -n200 weka fs tier fetch` |
| `--timeout` | Per-file submission timeout in integral seconds; 0 means indefinite timeout [default: 0] |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-v, --verbose` | Verbose output, showing fetch requests as they are submitted |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
