# Synopsis

```weka local events [--path path] [--json] [--raw-units] [--UTC]```

# Description

List the events saved to the local drive. This command does not require authentication and can be used when Weka is turned off.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--path` | Path to where local events are stored (default: /opt/weka/events) |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
