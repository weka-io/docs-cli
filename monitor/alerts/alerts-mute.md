# Synopsis

```weka alerts mute <alert-type> <duration> [--HOST HOST] [--PORT PORT] [--json]```

# Description

Mute an alert-type. Muted alerts will not be prompted when listing active alerts. Alerts cannot be suppressed indefinitely, so a duration must be supplied. Once the supplied duration has passed, the alert-type would be automatically unmuted

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `alert-type` | An alert-type to mute, use `weka alerts types` to list types |
| `duration` | How long to mute this alert type for (format: 3s, 2h, 4m, 1d, 1d5h, 1w) |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
