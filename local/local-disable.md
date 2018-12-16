# Synopsis

```weka local disable [--type type]... [<container>]...```

# Description

Disable containers by not launching them on machine boot. This does not affect the current running status of the container. In order to change the current status, use the "weka local start/stop" commands. If no container names are specified, this command runs on all containers.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>-t, --type</pre> | The container types to disable |
