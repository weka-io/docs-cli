# Synopsis

```weka cluster host memory <host-id> <memory> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]```

# Description

Dedicate host's RAM to weka

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>host-id</pre> | Host ID as shown in `weka cluster host` |
| <pre>memory</pre> | Memory dedicated to weka in bytes. Set to 0 to let weka decide. |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
