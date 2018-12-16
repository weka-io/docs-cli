# Synopsis

```weka nfs interface-group add <name> <type> [--subnet subnet] [--gateway gateway] [--HOST HOST] [--PORT PORT] [--json]```

# Description

Create an interface group

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>name</pre> | Interface group name |
| <pre>type</pre> | Group type. cli subnet type can be NFS |
| <pre>--subnet</pre> | subnet mask in the 255.255.0.0 format |
| <pre>--gateway</pre> | gateway ip |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
