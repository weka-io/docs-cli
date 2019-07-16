# Synopsis

```weka events list-local [--start-time <start>]
                       [--end-time <end>]
                       [--next next]
                       [--HOST HOST]
                       [--PORT PORT]
                       [--stem-mode]
                       [--show-internal]
                       [--server-timezone]
                       [--json]```

# Description

List recent events that happened on the machine running this command

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--start-time` | Include events occurred in this time point and later. Formatting examples: 5m, -5m, -1d, -1w, 1:00, 01:00, 18:30, 18:30:07, 2018-12-31 10:00, 2018/12/31 10:00, 2018-12-31T10:00, 9:15Z, 10:00+2:00 |
| `--end-time` | Include events occurred not later then this time point. Formatting examples: 5m, -5m, -1d, -1w, 1:00, 01:00, 18:30, 18:30:07, 2018-12-31 10:00, 2018/12/31 10:00, 2018-12-31T10:00, 9:15Z, 10:00+2:00 |
| `--next` | Token for the next page of events |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--stem-mode` | List stem mode events |
| `--show-internal` | Show internal events |
| `--server-timezone` | Use the server's timezone instead of the local one |
| `-J, --json` | Format output as JSON |
