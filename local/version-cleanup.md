# Synopsis

```weka version cleanup <container> [--version-name version-name]... [--force]```

# Description

Cleans up all traces of the specified version from the host, as though it was never run on it. It doesn't remove the version's images, for that `weka version rm-version` should be used. WARNING - This action is destructive and might cause a loss of data!

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `container` | The container to cleanup |
| `--version-name` | The versions to cleanup |
| `--force` | Force the action to actually happen |
