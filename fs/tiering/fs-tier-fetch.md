# Synopsis

```weka fs tier fetch [--timeout timeout] [--HOST HOST] [--PORT PORT] [--verbose] [--json] [--NO-HUMAN] [<path>]...```

# Description

Fetch object-stored files to SSD storage

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>--timeout</pre> | Per-file submission timeout in integral seconds; 0 means indefinite timeout [default: 0] |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-v, --verbose</pre> | Verbose output, showing fetch requests as they are submitted |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
