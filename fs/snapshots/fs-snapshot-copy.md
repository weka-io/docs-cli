# Synopsis

```weka fs snapshot copy <file-system> <source-name> <destination-name> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]```

# Description

Copy one snapshot over another

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>file-system</pre> | Source Filesystem name |
| <pre>source-name</pre> | Source snapshot name |
| <pre>destination-name</pre> | Destination snapshot name |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
