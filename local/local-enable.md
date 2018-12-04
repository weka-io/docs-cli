```
Usage:
local enable [--type type]... [<container>]...

Description:
    Enable monitoring for the requested containers so they automaticlly start on machine boot. This does not affect the
    current running status of the container. In order to change the current status, use the "weka local start/stop"
    commands. If no container names are specified, this command runs on all containers.

Options:
   -t, --type   The container types to enable
```
