# Synopsis

```weka fs create <name>
               <group-name>
               <total-capacity>
               [--ssd-capacity ssd-capacity]
               [--max-files max-files]
               [--filesystem-id filesystem-id]
               [--HOST HOST]
               [--PORT PORT]
               [--json]
               [--NO-HUMAN]```

# Description

Create a filesystem

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | Filesystem name |
| `group-name` | Group name |
| `total-capacity` | Total capacity [B&#124;KiB&#124;MiB&#124;GiB&#124;TiB&#124;PiB&#124;EiB&#124;ZiB&#124;YiB&#124;KB&#124;MB&#124;GB&#124;TB&#124;PB&#124;EB&#124;ZB&#124;YB] |
| `--ssd-capacity` | SSD capacity [B&#124;KiB&#124;MiB&#124;GiB&#124;TiB&#124;PiB&#124;EiB&#124;ZiB&#124;YiB&#124;KB&#124;MB&#124;GB&#124;TB&#124;PB&#124;EB&#124;ZB&#124;YB] |
| `--max-files` | Max files |
| `--filesystem-id` | Filesystem ID |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
