# Synopsis

```weka local run [--container container] [--in in] [--environment environment]... [--without-agent] [<command>]...```

# Description

Execute a command inside a new container that has the same mounts as the given container. If no container is specified, either "default" or the only defined container is selected. If not command is specified, opens an interactive shell.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>-C, --container</pre> | The container to run in |
| <pre>--in</pre> | The container version to run the command in |
| <pre>-e, --environment</pre> | Environemnt variable to add |
| <pre>--without-agent</pre> | Assume that the agent isn't running and run the container without it |
