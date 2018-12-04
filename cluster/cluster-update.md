```
Usage:
cluster update [--cluster-name cluster-name]
               [--data-drives data-drives]
               [--parity-drives parity-drives]
               [--scrubber-bytes-per-sec scrubber-bytes-per-sec]
               [--HOST HOST]
               [--PORT PORT]
               [--json]

Description:
    Update cluster configuration

Options:
   --cluster-name             Cluster name. Can't be configured after registering the cluster in the cloud
   --data-drives              Number of RAID data drives
   --parity-drives            Number of RAID protection parity drives
   --scrubber-bytes-per-sec   Rate of RAID scrubbing in units per second, for example: 5 is 5b/s, 5MiB is 5MiB/s (must
                              be positive)
   -H, --HOST                 Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT                 Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json                 Format output as JSON
```
