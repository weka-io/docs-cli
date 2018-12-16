# Synopsis

```weka fs tier s3 add <name>
                    [--hostname hostname]
                    [--port port]
                    [--bucket bucket]
                    [--auth-method auth-method]
                    [--region region]
                    [--access-key-id access-key-id]
                    [--secret-key secret-key]
                    [--protocol protocol]
                    [--bandwidth bandwidth]
                    [--errors-timeout errors-timeout]
                    [--prefetch-mib prefetch-mib]
                    [--HOST HOST]
                    [--PORT PORT]
                    [--dry-run]
                    [--skip-verification]
                    [--verbose-errors]
                    [--json]
                    [--NO-HUMAN]```

# Description

Create a new S3 object storage connection

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>name</pre> | Name of the Object Storage |
| <pre>--hostname</pre> | Hostname (or IP) of the entrypoint to the storage |
| <pre>--port</pre> | Port of the entrypoint to S3 (single Accesser or Load-Balancer) |
| <pre>--bucket</pre> | Name of the bucket we are assigned to work with |
| <pre>--auth-method</pre> | Authentication method. S3AuthMethod can be None, AWSSignature2 or AWSSignature4 |
| <pre>--region</pre> | Name of the region we are assigned to work with (usually empty) |
| <pre>--access-key-id</pre> | Access Key ID for AWS Signature authentications |
| <pre>--secret-key</pre> | Secret Key for AWS Signature authentications |
| <pre>--protocol</pre> | One of: HTTP (default), HTTPS, HTTPS_UNVERIFIED |
| <pre>--bandwidth</pre> | Bandwidth limitation per core (Mbps) |
| <pre>--errors-timeout</pre> | If the OBS link is down for longer than this, all IO's that need data return with an error refer to the 'Duration Switches Syntax' section in 'weka --help-syntax' for help regarding duration typed switches |
| <pre>--prefetch-mib</pre> | How many MiB of data to prefetch when reading a whole MiB on object store |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--dry-run</pre> | Only test the command, don't affect the system |
| <pre>--skip-verification</pre> | Don't verify the connection to the given storage |
| <pre>--verbose-errors</pre> | Dump HTTP info on error |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
