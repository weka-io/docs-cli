# Synopsis

```weka fs tier fetch [--timeout timeout] [--HOST HOST] [--PORT PORT] [--verbose] [--NO-HUMAN] [<path>]...```

# Description

Fetch object-stored files to SSD storage

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--timeout` | Per-file submission timeout in integral seconds; 0 means indefinite timeout [default: 0] |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-v, --verbose` | Verbose output, showing fetch requests as they are submitted |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
