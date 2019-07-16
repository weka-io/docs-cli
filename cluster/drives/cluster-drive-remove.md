# Synopsis

```weka cluster drive remove [--HOST HOST] [--PORT PORT] [--force] [--json] [--raw-units] [--UTC] [<uuids>]...```

# Description

Remove the supplied drive(s)

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `uuids` | A list of drive UUIDs to remove. A UUID is a hex string formatted as 8-4-4-4-12 e.g. 'abcdef12-1234-abcd-1234-1234567890ab' |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-f, --force` | Force this action without further confirmation (this command removes a drive from the system and can be undone by re-adding the drive and scanning drives on its attached host) |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
