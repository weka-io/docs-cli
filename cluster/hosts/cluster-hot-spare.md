# Synopsis

```weka cluster hot-spare [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN] [<count>]...```

# Description

Get or set the number of hot-spare failure-domains in the cluster. If <count> param is not given, the current number of hot-spare FDs will be listed

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
