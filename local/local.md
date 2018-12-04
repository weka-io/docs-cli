```
Usage:
local 

Description:
    Commands that control weka and it's containers on the local machine

Subcommands:
   install-agent   Installs WekaIO agent on the machine the command is executed from
   ps              List the Weka containers running on the machine this command is executed from
   setup           Setup a local weka container
   rm              Delete a Weka container from the machine this command is executed from (without removing it's
                   images)
   start           Start a Weka container
   stop            Stop a Weka container
   restart         Restart a Weka container
   status          Show the status of a Weka container
   enable          Enable monitoring for the requested containers so they automaticlly start on machine boot. This does
                   not affect the current running status of the container. In order to change the current status, use
                   the "weka local start/stop" commands. If no container names are specified, this command runs on all
                   containers.
   disable         Disable containers by not launching them on machine boot. This does not affect the current running
                   status of the container. In order to change the current status, use the "weka local start/stop"
                   commands. If no container names are specified, this command runs on all containers.
   monitoring      Turn monitoring on/off for the given containers, or all containers is none are specified. When a
                   container is started, its always monitored. When a container is monitored, it will be restarted if
                   it exits without being stopped through the CLI.
   diags           Collect diagnostics from the machine this command was executed from
   exec            Execute a command inside a currently running container. If not command is specified, open an
                   interactive shell.
   run             Execute a command inside a new container that has the same mounts as the given container. If no
                   container is specified, either "default" or the only defined container is selected. If not command
                   is specified, opens an interactive shell.

```
