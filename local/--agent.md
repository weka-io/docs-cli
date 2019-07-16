# Synopsis

```weka --agent [--set-version set-version] [--timeout timeout]```

# Description

Start the agent service

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--set-version` | Use the specified version as the current version, without changing anything. Intended for internal use only |
| `--timeout` | Time to sleep before stopping the container and exiting. This is a dangerous parameter, do not pass it. Doing so incorrectly might risk the cluster (format: 3s, 2h, 4m, 1d, 1d5h, 1w) |
