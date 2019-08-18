# Synopsis

```weka cluster stop-io [--HOST HOST] [--PORT PORT] [--brutal-no-flush] [--force]```

# Description

Stop IO services

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--brutal-no-flush` | Force stopping IO services immediately without graceful flushing of ongoing operations. Using this flag may cause data-loss if used without explicit guidance from WekaIO customer support. |
| `-f, --force` | Force this action without further confirmation (this command will disrupt operation and will only be undone by running 'weka cluster start-io') |
