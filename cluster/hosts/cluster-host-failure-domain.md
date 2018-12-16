# Synopsis

```weka cluster host failure-domain <host-id>
                                 [--name name]
                                 [--HOST HOST]
                                 [--PORT PORT]
                                 [--auto]
                                 [--ha]
                                 [--json]
                                 [--NO-HUMAN]```

# Description

Set the host failure-domain

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>host-id</pre> | Host ID as shown in `weka cluster host` |
| <pre>--name</pre> | Add this host to a named failure-domain. A failure-domain will be created if it doesn't exist yet. |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--auto</pre> | Set this host to be a failure-domain of its own |
| <pre>--ha</pre> | Mark this host as highly available |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
