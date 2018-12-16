# Synopsis

```weka fs group update <name>
                     [--new-name new-name]
                     [--is-tiered is-tiered]
                     [--storage storage]
                     [--target-ssd-retention target-ssd-retention]
                     [--start-demote start-demote]
                     [--HOST HOST]
                     [--PORT PORT]
                     [--json]
                     [--NO-HUMAN]```

# Description

Update a filesystem group

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | The filesystem group name to be created |
| `--new-name` | Updated name of the fspecified ilesystem group |
| `--is-tiered` | Is the filesystem-group tiered (yes/no) |
| `--storage` | Name of the Object Storage linked with the group |
| `--target-ssd-retention` | Period of time to keep an SSD copy of the data |
| `--start-demote` | Period of time to wait before copying data to the Object Storage |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
