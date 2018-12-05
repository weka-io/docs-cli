```
Usage:
fs tier s3 update <name>
                  [--new-name new-name]
                  [--hostname hostname]
                  [--port port]
                  [--protocol protocol]
                  [--bucket bucket]
                  [--auth-method auth-method]
                  [--region region]
                  [--access-key-id access-key-id]
                  [--secret-key secret-key]
                  [--bandwidth bandwidth]
                  [--prefetch-mib prefetch-mib]
                  [--errors-timeout errors-timeout]
                  [--HOST HOST]
                  [--PORT PORT]
                  [--dry-run]
                  [--skip-verification]
                  [--verbose-errors]
                  [--json]
                  [--NO-HUMAN]

Description:
    Edit an existing S3 object storage connection

Arguments:
   name   Name of the Object Storage
Options:
   --new-name            New name
   --hostname            Hostname (or IP) of the entrypoint to the storage
   --port                Port of the entrypoint to S3 (single Accesser or Load-Balancer)
   --protocol            One of: HTTP (default), HTTPS, HTTPS_UNVERIFIED
   --bucket              Name of the bucket we are assigned to work with
   --auth-method         Authentication method. S3AuthMethod can be None, AWSSignature2 or AWSSignature4
   --region              Name of the region we are assigned to work with (usually empty)
   --access-key-id       Access Key ID for AWS Signature authentications
   --secret-key          Secret Key for AWS Signature authentications
   --bandwidth           Bandwidth limitation per core (Mbps)
   --prefetch-mib        How many MiB of data to prefetch when reading a whole MiB on object store
   --errors-timeout      If the OBS link is down for longer than this, all IO's that need data return with an error
                         refer to the 'Duration Switches Syntax' section in 'weka --help-syntax' for help regarding
                         duration typed switches
   -H, --HOST            Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT            Specify the port. Alternatively, use the WEKA_PORT env variable
   --dry-run             Only test the command, don't affect the system
   --skip-verification   Don't verify the connection to the given storage
   --verbose-errors      Dump HTTP info on error
   -J, --json            Format output as JSON
   -N, --NO-HUMAN        Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB
                         234MiB 2GiB.
```
