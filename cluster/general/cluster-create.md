# Synopsis

```weka cluster create [--HOST HOST] [--PORT PORT] [--host-ips host-ips]... [--json] [<host-hostnames>]...```

# Description

Form a Weka cluster from hosts that just has Weka installed on them

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--host-ips</pre> | Management IP addresses; If empty, the hostnames will be resolved |
| <pre>-J, --json</pre> | Format output as JSON |
