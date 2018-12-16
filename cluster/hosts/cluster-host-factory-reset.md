# Synopsis

```weka cluster host factory-reset <guid>
                                [--HOST HOST]
                                [--PORT PORT]
                                [--force]
                                [--json]
                                [--NO-HUMAN]
                                [<hostnames-or-ips>]...```

# Description

Factory resets the hosts. NOTE! this can't be undone!

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>guid</pre> | The cluster GUID |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--force</pre> | When set, broute force reset |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
