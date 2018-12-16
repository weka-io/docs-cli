# Synopsis

```weka events list-types [--HOST HOST] [--PORT PORT] [--category category]... [--type type]... [--show-internal] [--json]```

# Description

Show the event type definition information

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--category</pre> | List only events of the specified categories Category can be Events, Node, Raid, Disk, SSD, ObjectStorage, System, IO, Clustering, Statistics, Network, Filesystem, Upgrade, NFS, Config, Cloud, InterfaceGroup or Custom |
| <pre>--type</pre> | List only events of the specified types |
| <pre>--show-internal</pre> | Show internal events |
| <pre>-J, --json</pre> | Format output as JSON |
