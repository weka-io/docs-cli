# Synopsis

```weka version cleanup <container> [--version-name version-name]... [--force]```

# Description

Cleans up all traces of the specified version from the host, as though it was never run on it. It doesn't remove the version's images, for that `weka version rm` should be used. WARNING - This action is destructive and might cause a loss of data!

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `container` | The container to cleanup |
| `--version-name` | The versions to cleanup |
| `-f, --force` | Force this action without further confirmation (this command deletes the version and would not allow running this version without downloading it again) |
