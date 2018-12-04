```
Usage:
cloud update <bucket-name>
             <region>
             <access-key-id>
             <secret-key>
             [--session-token <token>]
             [--bucket-prefix <prefix>]
             [--proxy proxy]
             [--bytes-per-second bytes-per-second]
             [--HOST HOST]
             [--PORT PORT]
             [--json]

Description:
    Update cloud settings

Arguments:
   bucket-name     AWS bucket name
   region          AWS region
   access-key-id   AWS access key
   secret-key      AWS secret
Options:
   --session-token      S3 session token
   --bucket-prefix      S3 bucket prefix
   --proxy              HTTP(S) proxy to connect to the cloud through
   --bytes-per-second   Maximum uploaded bytes per second
   -H, --HOST           Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT           Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json           Format output as JSON
```
