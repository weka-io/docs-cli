# Synopsis

```weka cluster host info-hw [--HOST HOST] [--PORT PORT] [--info-type info-type]... [--json] [--NO-HUMAN] [<hostnames>]...```

# Description

Show hardware information about one or more hosts

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--info-type</pre> | Specify which HW info to retrieve, can be version&#124;osinfo&#124;memory&#124;cores&#124;disks&#124;eths&#124;net&#124;IPs |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
