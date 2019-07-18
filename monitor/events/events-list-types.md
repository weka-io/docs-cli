# Synopsis

```weka events list-types [--HOST HOST] [--PORT PORT] [--category category]... [--type type]... [--show-internal] [--json]```

# Description

Show the event type definition information

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-c, --category` | List only events of the specified categories Category can be Events, Node, Raid, Disk, SSD, ObjectStorage, System, IO, Clustering, Statistics, Network, Filesystem, Upgrade, NFS, Config, Cloud, InterfaceGroup or Custom |
| `-t, --type` | List only events of the specified types |
| `--show-internal` | Show internal events |
| `-J, --json` | Format output as JSON |
