# Synopsis

```weka events [--num-results num-results]
            [--start-time <start>]
            [--end-time <end>]
            [--severity severity]
            [--sort-order sort-order]
            [--HOST HOST]
            [--PORT PORT]
            [--type-list type-list]...
            [--exclude-type-list exclude-type-list]...
            [--category-list category-list]...
            [--by-digested-time]
            [--show-internal]
            [--json]
            [--raw-units]
            [--UTC]```

# Description

List all events that conform to the filter criteria

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-n, --num-results` | Get up to this number of events, default: 50 |
| `--start-time` | Include events occurred in this time point and later (format: 5m, -5m, -1d, -1w, 1:00, 01:00, 18:30, 18:30:07, 2018-12-31 10:00, 2018/12/31 10:00, 2018-12-31T10:00, 9:15Z, 10:00+2:00) |
| `--end-time` | Include events occurred not later then this time point (format: 5m, -5m, -1d, -1w, 1:00, 01:00, 18:30, 18:30:07, 2018-12-31 10:00, 2018/12/31 10:00, 2018-12-31T10:00, 9:15Z, 10:00+2:00) |
| `-s, --severity` | Include event with equal and higher severity, default: INFO (format: 'info', 'warning', 'minor', 'major' or 'critical') |
| `--sort-order` | Sort the events by ascending or descending time, default: asc (format: 'asc' or 'dsc') |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-t, --type-list` | Filter events by type, can be used multiple times (use 'weka events list-types' to see available types) |
| `-x, --exclude-type-list` | Remove events by type, can be used multiple times (use 'weka events list-types' to see available types) |
| `-c, --category-list` | Include only events matches to the category_list. Category can be Events, Node, Raid, Disk, SSD, ObjectStorage, System, IO, Clustering, Statistics, Network, Filesystem, Upgrade, NFS, Config, Cloud, InterfaceGroup or Custom |
| `--by-digested-time` | Query and sort result by digested time |
| `-i, --show-internal` | Show internal events |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
