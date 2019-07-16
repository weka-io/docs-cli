# Synopsis

```weka stats [--start-time <start>]
           [--end-time <end>]
           [--interval interval]
           [--resolution-secs <secs>]
           [--HOST HOST]
           [--PORT PORT]
           [--category category]...
           [--stat stat]...
           [--node-ids node-ids]...
           [--param param]...
           [--accumulated]
           [--per-node]
           [--no-zeros]
           [--show-internal]
           [--json]
           [--raw-units]
           [--UTC]```

# Description

List all statistics that conform to the filter criteria

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--start-time` | Query for stats starting at this time (format: 5m, -5m, -1d, -1w, 1:00, 01:00, 18:30, 18:30:07, 2018-12-31 10:00, 2018/12/31 10:00, 2018-12-31T10:00, 9:15Z, 10:00+2:00) |
| `--end-time` | Query for stats up to this time point (format: 5m, -5m, -1d, -1w, 1:00, 01:00, 18:30, 18:30:07, 2018-12-31 10:00, 2018/12/31 10:00, 2018-12-31T10:00, 9:15Z, 10:00+2:00) |
| `--interval` | Period (in seconds) of time of the report |
| `--resolution-secs` | Length of each interval in the report period |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--category` | Retrieve only statistics of the specified categories |
| `--stat` | Retrieve only the specified statistics |
| `--node-ids` | Limit the report to the specified nodes |
| `--param` | For parameterized statistics, retrieve only the instantiations where the specified parameter is of the specified value. Multiple values can be supplied for the same key, e.g. '--param method:putBlocks --param method:initBlock'. (format: key:value) |
| `--accumulated` | Show accumulated statistics, not rate statistics |
| `--per-node` | Do not aggregate statistics across nodes |
| `-Z, --no-zeros` | Do not retrieve results where the value is 0 |
| `--show-internal` | Show internal statistics |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
