# Synopsis

```weka diags --upload [--cores cores] [--HOST HOST] [--PORT PORT] [--clients]```

# Description

Collect and upload diags from all cluster hosts to Weka's support cloud

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--cores` | Limit to processing this number of core dumps, if found (default: 1) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--clients` | Collect diags from clients as well as backends (by default diags are only collected from backends) |
