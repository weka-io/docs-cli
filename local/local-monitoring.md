# Synopsis

```weka local monitoring <enabled> [--type type]... [<container>]...```

# Description

Turn monitoring on/off for the given containers, or all containers if none are specified. When a container is started, it's always monitored. When a container is monitored, it will be restarted if it exits without being stopped through the CLI.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `enabled` | Whether monitoring should be on or off (format: 'on' or 'off') |
| `container` | The container to disable |
| `-t, --type` | The container types to disable |
