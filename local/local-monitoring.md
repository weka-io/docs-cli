# Synopsis

```weka local monitoring <change> [--type type]... [<container>]...```

# Description

Turn monitoring on/off for the given containers, or all containers is none are specified. When a container is started, its always monitored. When a container is monitored, it will be restarted if it exits without being stopped through the CLI.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>change</pre> | Turn the monitoring on or off |
| <pre>-t, --type</pre> | The container types to disable |
