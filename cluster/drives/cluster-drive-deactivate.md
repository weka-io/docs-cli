# Synopsis

```weka cluster drive deactivate [--HOST HOST]
                              [--PORT PORT]
                              [--skip-resource-validation]
                              [--json]
                              [--NO-HUMAN]
                              [<uuids>]...```

# Description

Deactivate the supplied drive(s)

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--skip-resource-validation` | Skip verifying that the cluster will still have enough RAM and SSD resources after deactivating the drives |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
