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
                    [--max-concurrent-downloads max-concurrent-downloads]
                    [--max-concurrent-uploads max-concurrent-uploads]
                    [--max-concurrent-removals max-concurrent-removals]
                    [--HOST HOST]
                    [--PORT PORT]
                    [--dry-run]
                    [--skip-verification]
                    [--verbose-errors]
                    [--json]
                    [--raw-units]
                    [--UTC]```

# Description

Create a new S3 object storage connection

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | Name of the Object Storage |
| `--hostname` | Hostname (or IP) of the entrypoint to the storage |
| `--port` | Port of the entrypoint to S3 (single Accesser or Load-Balancer) |
| `--bucket` | Name of the bucket we are assigned to work with |
| `--auth-method` | Authentication method. S3AuthMethod can be None, AWSSignature2 or AWSSignature4 |
| `--region` | Name of the region we are assigned to work with (usually empty) |
| `--access-key-id` | Access Key ID for AWS Signature authentications |
| `--secret-key` | Secret Key for AWS Signature authentications |
| `--protocol` | One of: HTTP (default), HTTPS, HTTPS_UNVERIFIED |
| `--bandwidth` | Bandwidth limitation per core (Mbps) |
| `--errors-timeout` | If the OBS link is down for longer than this, all IO's that need data return with an error (format: 3s, 2h, 4m, 1d, 1d5h, 1w) |
| `--prefetch-mib` | How many MiB of data to prefetch when reading a whole MiB on object store |
| `--max-concurrent-downloads` | Maximum number of downloads we concurrently perform on this object store in a single IO node |
| `--max-concurrent-uploads` | Maximum number of uploads we concurrently perform on this object store in a single IO node |
| `--max-concurrent-removals` | Maximum number of removals we concurrently perform on this object store in a single IO node |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--dry-run` | Only test the command, don't affect the system |
| `--skip-verification` | Don't verify the connection to the given storage |
| `--verbose-errors` | Dump HTTP info on error |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
