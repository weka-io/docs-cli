# Synopsis

```weka cluster create [--HOST HOST] [--PORT PORT] [--host-ips host-ips]... [--json] [<host-hostnames>]...```

# Description

Form a Weka cluster from hosts that just has Weka installed on them

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-hostnames` | A list of hostname to be included in the new cluster |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--host-ips` | Management IP addresses; If empty, the hostnames will be resolved; If hosts are highly-available, use IP pairs '<ip>+<ip>'; |
| `-J, --json` | Format output as JSON |
