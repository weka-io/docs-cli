# Synopsis

```weka cluster update [--cluster-name cluster-name]
                    [--data-drives data-drives]
                    [--parity-drives parity-drives]
                    [--scrubber-bytes-per-sec scrubber-bytes-per-sec]
                    [--HOST HOST]
                    [--PORT PORT]
                    [--json]```

# Description

Update cluster configuration

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>--cluster-name</pre> | Cluster name. Can't be configured after registering the cluster in the cloud |
| <pre>--data-drives</pre> | Number of RAID data drives |
| <pre>--parity-drives</pre> | Number of RAID protection parity drives |
| <pre>--scrubber-bytes-per-sec</pre> | Rate of RAID scrubbing in units per second, for example: 5 is 5b/s, 5MiB is 5MiB/s (must be positive) |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
