# Synopsis

```weka fs update <name>
               [--new-name new-name]
               [--total-capacity total-capacity]
               [--ssd-capacity ssd-capacity]
               [--max-files max-files]
               [--HOST HOST]
               [--PORT PORT]
               [--json]
               [--NO-HUMAN]```

# Description

Update a filesystem

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>name</pre> | Filesystem name |
| <pre>--new-name</pre> | New name |
| <pre>--total-capacity</pre> | Total capacity [B&#124;KiB&#124;MiB&#124;GiB&#124;TiB&#124;PiB&#124;EiB&#124;ZiB&#124;YiB&#124;KB&#124;MB&#124;GB&#124;TB&#124;PB&#124;EB&#124;ZB&#124;YB] |
| <pre>--ssd-capacity</pre> | SSD capacity [B&#124;KiB&#124;MiB&#124;GiB&#124;TiB&#124;PiB&#124;EiB&#124;ZiB&#124;YiB&#124;KB&#124;MB&#124;GB&#124;TB&#124;PB&#124;EB&#124;ZB&#124;YB] |
| <pre>--max-files</pre> | Max files |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
