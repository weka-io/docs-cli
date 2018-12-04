```
Usage:
local monitoring <change> [--type type]... [<container>]...

Description:
    Turn monitoring on/off for the given containers, or all containers is none are specified. When a container is
    started, its always monitored. When a container is monitored, it will be restarted if it exits without being
    stopped through the CLI.

Arguments:
   change   Turn the monitoring on or off
Options:
   -t, --type   The container types to disable
```
