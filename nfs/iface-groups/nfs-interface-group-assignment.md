# Synopsis

```weka nfs interface-group assignment [--name name] [--HOST HOST] [--PORT PORT] [--json]```

# Description

List the currently assigned interface for each floating-IP address in the given interface-group. If <name> is not supplied, assignments for all floating-IP addresses will be listed

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>--name</pre> | Group name |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
