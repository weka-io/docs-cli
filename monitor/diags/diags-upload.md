# Synopsis

```weka diags upload [--timeout timeout]
                  [--core-limit core-limit]
                  [--HOST HOST]
                  [--PORT PORT]
                  [--host-id host-id]...
                  [--clients]
                  [--no-wait]
                  [<id>]...```

# Description

Collect and upload diags from all cluster hosts to Weka's support cloud

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `id` | ID of an existing dump to upload. This dump ID has to exist on this local machine. If a previous diags collection happened on some of the hosts you're trying to upload from, those hosts will fail with the diags ID being missing. If a diags ID is not specified, a new dump is created for this upload. |
| `-T, --timeout` | How long to wait for diags to upload. Default is 10 minutes, 0 means indefinite (format: 3s, 2h, 4m, 1d, 1d5h, 1w) |
| `-c, --core-limit` | Limit to processing this number of core dumps, if found (default: 1) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--host-id` | Host IDs to collect diags from, can be used multiple times. This flag causes --clients to be ignored. |
| `--clients` | Collect diags from clients as well as backends (by default diags are only collected from backends) |
| `-W, --no-wait` | Don't wait for upload to finish |
