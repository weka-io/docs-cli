# Synopsis

```weka cloud update <bucket-name>
                  <region>
                  <access-key-id>
                  <secret-key>
                  [--session-token <token>]
                  [--bucket-prefix <prefix>]
                  [--proxy proxy]
                  [--bytes-per-second bytes-per-second]
                  [--HOST HOST]
                  [--PORT PORT]
                  [--json]```

# Description

Update cloud settings

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>bucket-name</pre> | AWS bucket name |
| <pre>region</pre> | AWS region |
| <pre>access-key-id</pre> | AWS access key |
| <pre>secret-key</pre> | AWS secret |
| <pre>--session-token</pre> | S3 session token |
| <pre>--bucket-prefix</pre> | S3 bucket prefix |
| <pre>--proxy</pre> | HTTP(S) proxy to connect to the cloud through |
| <pre>--bytes-per-second</pre> | Maximum uploaded bytes per second |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
