# Synopsis

```weka alerts mute <alert-type> <duration> [--HOST HOST] [--PORT PORT] [--json]```

# Description

Mute an alert-type. Muted alerts will not be prompted when listing active alerts. Alerts cannot be suppressed indefinitely, so a duration must be supplied. Once the supplied duration has passed, the alert-type would be automatically unmuted

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>alert-type</pre> | An alert-type to mute, use `weka alerts types` to list types |
| <pre>duration</pre> | Dismissal duration in time-parts syntax: (<number> <unit>)* e.g. '180 days', '1 week' see the 'Duration' section in '--help-syntax' for further details |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
