```
Usage:
events list-types [--HOST HOST] [--PORT PORT] [--category category]... [--type type]... [--show-internal] [--json]

Description:
    Show the event type definition information

Options:
   -H, --HOST        Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT        Specify the port. Alternatively, use the WEKA_PORT env variable
   --category        List only events of the specified categories Category can be Events, Node, Raid, Disk, SSD,
                     ObjectStorage, System, IO, Clustering, Statistics, Network, Filesystem, Upgrade, NFS, Config,
                     Cloud, InterfaceGroup or Custom
   --type            List only events of the specified types
   --show-internal   Show internal events
   -J, --json        Format output as JSON
```
