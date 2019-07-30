# Synopsis

```weka local reset-data [--container container] [--force]```

# Description

Resets the data directory for a given container, making the host no longer aware of the rest of the cluster and deleting all logs

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-C, --container` | The container to run in |
| `-f, --force` | Force this action without further confirmation (this command is destructive and will only be undone by re-adding the host to the cluster) |
