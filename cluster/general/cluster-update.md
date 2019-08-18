# Synopsis

```weka cluster update [--cluster-name cluster-name]
                    [--data-drives data-drives]
                    [--parity-drives parity-drives]
                    [--scrubber-bytes-per-sec scrubber-bytes-per-sec]
                    [--HOST HOST]
                    [--PORT PORT]
                    [--json]```

# Description

Update cluster configuration

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--cluster-name` | Cluster name |
| `--data-drives` | Number of RAID data drives |
| `--parity-drives` | Number of RAID protection parity drives |
| `--scrubber-bytes-per-sec` | Rate of RAID scrubbing in units per second (format: capacity in decimal or binary units: 11B, 1KB, 1MB, 1GB, 1TB, 1PB, 1EB, 1ZB, 1YB, 1KiB, 1MiB, 1GiB, 1TiB, 1PiB, 1EiB, 1ZiB, 1YiB) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
