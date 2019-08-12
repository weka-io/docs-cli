# Synopsis

```weka fs download <name>
                 <group-name>
                 <total-capacity>
                 <ssd-capacity>
                 <locator>
                 [--max-files max-files]
                 [--HOST HOST]
                 [--PORT PORT]
                 [--skip-resource-validation]
                 [--json]
                 [--raw-units]
                 [--UTC]```

# Description

Download a filesystem from object store

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | Filesystem name |
| `group-name` | Group name |
| `total-capacity` | Total capacity (format: capacity in decimal or binary units: 11B, 1KB, 1MB, 1GB, 1TB, 1PB, 1EB, 1ZB, 1YB, 1KiB, 1MiB, 1GiB, 1TiB, 1PiB, 1EiB, 1ZiB, 1YiB) |
| `ssd-capacity` | SSD capacity (format: capacity in decimal or binary units: 11B, 1KB, 1MB, 1GB, 1TB, 1PB, 1EB, 1ZB, 1YB, 1KiB, 1MiB, 1GiB, 1TiB, 1PiB, 1EiB, 1ZiB, 1YiB) |
| `locator` | Locator |
| `--max-files` | Max files |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--skip-resource-validation` | Skip verifying that the cluster has enough RAM and SSD resources allocated for the downloaded filesystem |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
