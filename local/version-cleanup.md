# Synopsis

```weka version cleanup <container> [--version-name version-name]... [--force]```

# Description

Cleans up all traces of the specified version from the host, as though it was never run on it. It doesn't remove the version's images, for that `weka version rm-version` should be used. WARNING - This action is destructive and might cause a loss of data!

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>container</pre> | The container to cleanup |
| <pre>--version-name</pre> | The versions to cleanup |
| <pre>--force</pre> | Force the action to actually happen |
