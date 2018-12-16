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
| `name` | Filesystem name |
| `--new-name` | New name |
| `--total-capacity` | Total capacity [B|KiB|MiB|GiB|TiB|PiB|EiB|ZiB|YiB|KB|MB|GB|TB|PB|EB|ZB|YB] |
| `--ssd-capacity` | SSD capacity [B|KiB|MiB|GiB|TiB|PiB|EiB|ZiB|YiB|KB|MB|GB|TB|PB|EB|ZB|YB] |
| `--max-files` | Max files |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
