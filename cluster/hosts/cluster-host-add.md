# Synopsis

```weka cluster host add <hostname>
                      [--ip ip]
                      [--auto-remove-timeout auto-remove-timeout]
                      [--HOST HOST]
                      [--PORT PORT]
                      [----no-wait]
                      [--json]
                      [--NO-HUMAN]```

# Description

Add a host to the cluster

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>hostname</pre> | Management network hostname |
| <pre>--ip</pre> | Management IP. If empty, the hostname is resolved. |
| <pre>--auto-remove-timeout</pre> | How long to wait (in seconds) before removing this host if it disconnects from the cluster. Minimum value is 60, use 0 to disable automatic removal (default). Only Available for clients. |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>----no-wait</pre> |  |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
