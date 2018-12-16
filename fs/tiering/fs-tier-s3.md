# Synopsis

```weka fs tier s3 [--name name] [--HOST HOST] [--PORT PORT] [--json] [--NO-HUMAN]```

# Description

List S3 object storage configuration and status

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>--name</pre> | Name of the Object Storage |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
