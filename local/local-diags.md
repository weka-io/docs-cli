# Synopsis

```weka local diags [--dump-id dump-id]
                 [--output output]
                 [--core-dump-limit core-dump-limit]
                 [--upload]
                 [--serve]
                 [--collect-cluster-info]```

# Description

Collect diagnostics from the machine this command was executed from

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--dump-id` | A unique identifier for this dump |
| `-o, --output` | Directory to save the diags dump to, if not given a random path is selected |
| `-c, --core-dump-limit` | Limit to processing this number of core dumps, if found (default: 0) |
| `--upload` | Upload dump to the cloud |
| `--serve` | Serve dump via the agent's http server |
| `-C, --collect-cluster-info` | Collect cluster-related information. Warning: Use this flag on one host at a time to avoid straining the cluster. |
