# Synopsis

```weka nfs rules add dns <name> <dns> [--ip ip] [--HOST HOST] [--PORT PORT] [--json]```

# Description

Add a DNS rule to an NFS client group

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>name</pre> | Group name |
| <pre>dns</pre> | DNS rule with *?[] wildcards rule |
| <pre>--ip</pre> | IP with netmask rule, in the 1.1.1.1/255.255.0.0 format |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
