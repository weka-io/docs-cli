# Synopsis

```weka cluster drive scan [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN] [<host-ids>]...```

# Description

Scan for provisioned drives on the cluster's hosts

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
