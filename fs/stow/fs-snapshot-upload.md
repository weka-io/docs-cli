# Synopsis

```weka fs snapshot upload <file-system> <snapshot> [--HOST HOST] [--PORT PORT] [--abort] [--json] [--NO-HUMAN]```

# Description

Upload a snapshot to object store

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>file-system</pre> | Filesystem name |
| <pre>snapshot</pre> | Snapshot name |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--abort</pre> | Abort in-progress upload |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
