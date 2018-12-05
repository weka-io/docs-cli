```
Usage:
local run [--container container] [--in in] [--environment environment]... [--without-agent] [<command>]...

Description:
    Execute a command inside a new container that has the same mounts as the given container. If no container is
    specified, either "default" or the only defined container is selected. If not command is specified, opens an
    interactive shell.

Options:
   -C, --container     The container to run in
   --in                The container version to run the command in
   -e, --environment   Environemnt variable to add
   --without-agent     Assume that the agent isn't running and run the container without it
```
