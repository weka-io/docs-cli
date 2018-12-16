# Synopsis

```weka cluster host activate [--HOST HOST] [--PORT PORT] [--no-wait] [--json] [--NO-HUMAN] [<host-ids>]...```

# Description

Activate the supplied hosts, or all hosts (if none supplied)

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--no-wait` |  |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
