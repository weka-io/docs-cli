# Synopsis

```weka cluster drive deactivate [--HOST HOST]
                              [--PORT PORT]
                              [--skip-resource-validation]
                              [--force]
                              [--json]
                              [--raw-units]
                              [--UTC]
                              [<uuids>]...```

# Description

Deactivate the supplied drive(s)

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--skip-resource-validation` | Skip verifying that the cluster will still have enough RAM and SSD resources after deactivating the drives |
| `-f, --force` | Force this action without further confirmation (this command may impact performance while the drive is phasing out and can be undone by activating the drive) |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
