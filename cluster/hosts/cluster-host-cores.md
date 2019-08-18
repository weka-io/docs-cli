# Synopsis

```weka cluster host cores <host-id>
                        <cores>
                        [--frontend-dedicated-cores frontend-dedicated-cores]
                        [--drives-dedicated-cores drives-dedicated-cores]
                        [--HOST HOST]
                        [--PORT PORT]
                        [--cores-ids cores-ids]...
                        [--json]
                        [--raw-units]
                        [--UTC]```

# Description

Dedicate host's cores to weka

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | Host ID as shown in `weka cluster host` |
| `cores` | Number of CPU cores dedicated to weka - If set to 0 - no drive could be added to this host |
| `--frontend-dedicated-cores` | Number of cores dedicated to weka frontend (out of the total <num-cores>) |
| `--drives-dedicated-cores` | Number of cores dedicated to weka drives (out of the total <num-cores>) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--cores-ids` | Specify the ids of weka dedicated cores. 'cores ids type' param will be set to USER |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
