# Synopsis

```weka local enable [--type type]... [<container>]...```

# Description

Enable monitoring for the requested containers so they automaticlly start on machine boot. This does not affect the current running status of the container. In order to change the current status, use the "weka local start/stop" commands. If no container names are specified, this command runs on all containers.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>-t, --type</pre> | The container types to enable |
