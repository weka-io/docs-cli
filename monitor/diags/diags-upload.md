# Synopsis

```weka diags upload [--timeout timeout] [--core-limit core-limit] [--HOST HOST] [--PORT PORT] [--clients] [--no-wait]```

# Description

Collect and upload diags from all cluster hosts to Weka's support cloud

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-T, --timeout` | How long to wait for diags to upload. Default is 10 minutes, 0 means indefinite (format: 3s, 2h, 4m, 1d, 1d5h, 1w) |
| `-c, --core-limit` | Limit to processing this number of core dumps, if found (default: 1) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--clients` | Collect diags from clients as well as backends (by default diags are only collected from backends) |
| `-W, --no-wait` | Don't wait for upload to finish |
