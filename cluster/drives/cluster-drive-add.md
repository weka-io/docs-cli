# Synopsis

```weka cluster drive add <host-id> <device-path> [--HOST HOST] [--PORT PORT] [--force] [--json] [--NO-HUMAN]```

# Description

Add the given drive

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>host-id</pre> | The host the drive attached to (given by ids) |
| <pre>device-path</pre> | The device path |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--force</pre> |  |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
