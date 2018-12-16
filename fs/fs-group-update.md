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
| <pre>name</pre> | The filesystem group name to be created |
| <pre>--new-name</pre> | Updated name of the fspecified ilesystem group |
| <pre>--is-tiered</pre> | Is the filesystem-group tiered (yes/no) |
| <pre>--storage</pre> | Name of the Object Storage linked with the group |
| <pre>--target-ssd-retention</pre> | Period of time to keep an SSD copy of the data |
| <pre>--start-demote</pre> | Period of time to wait before copying data to the Object Storage |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
