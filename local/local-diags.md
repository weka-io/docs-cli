# Synopsis

```weka local diags [--id id]
                 [--output-dir output-dir]
                 [--core-dump-limit core-dump-limit]
                 [--HOST HOST]
                 [--PORT PORT]
                 [--collect-cluster-info]
                 [--tar]
                 [--verbose]```

# Description

Collect diagnostics from the local machine

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-i, --id` | A unique identifier for this dump |
| `-d, --output-dir` | Directory to save the diags dump to, default: /opt/weka/diags |
| `-c, --core-dump-limit` | Limit to processing this number of core dumps, if found (default: 1) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-C, --collect-cluster-info` | Collect cluster-related information. Warning: Use this flag on one host at a time to avoid straining the cluster. |
| `-t, --tar` | Create a TAR of all collected diags |
| `-v, --verbose` | Print results of all diags, including successful ones |
