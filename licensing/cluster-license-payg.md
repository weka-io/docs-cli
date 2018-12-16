# Synopsis

```weka cluster license payg <plan-id>
                          <secret-key>
                          [--bucket-name bucket-name]
                          [--region region]
                          [--HOST HOST]
                          [--PORT PORT]
                          [--json]
                          [--NO-HUMAN]```

# Description

Enable pay-as-you-go for the cluster

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>plan-id</pre> |  |
| <pre>secret-key</pre> |  |
| <pre>--bucket-name</pre> | The name of the bucket to use |
| <pre>--region</pre> | The region to use |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
