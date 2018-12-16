# Synopsis

```weka cluster host dedicate <host-id> <on> [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]```

# Description

Set the host as dedicated to weka. For example it can be rebooted whenever needed, and configured by weka for optimal performance and stability

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>host-id</pre> | Host ID as shown in `weka cluster host` |
| <pre>on</pre> | Set the host as weka dedicated, off unsets host as weka dedicated |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
