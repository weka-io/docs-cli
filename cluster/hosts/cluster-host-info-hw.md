# Synopsis

```weka cluster host info-hw [--HOST HOST] [--PORT PORT] [--info-type info-type]... [--json] [--NO-HUMAN] [<hostnames>]...```

# Description

Show hardware information about one or more hosts

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--info-type` | Specify which HW info to retrieve, can be version|osinfo|memory|cores|disks|eths|net|IPs |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
