```
Usage:
events [--num-results num-results]
       [--start-time <start>]
       [--end-time <end>]
       [--severity severity]
       [--sort-order sort-order]
       [--fetch-order fetch-order]
       [--HOST HOST]
       [--PORT PORT]
       [--type-list type-list]...
       [--category-list category-list]...
       [--by-digested-time]
       [--show-internal]
       [--server-timezone]
       [--json]

Description:
    List all events that conform to the filter criteria

Subcommands:
   list-local   List recent events that happened on the machine running this command
   list-types   Show the event type definition information

Options:
   -n, --num-results    Maximal number of results
   --start-time         Include events occurred in this time point and later. Formatted like '2018-02-28T14:00:00'
   --end-time           Include events occurred not later then this time point. Formatted like '2018-02-28T14:00:00'
   --severity           Include event with equal and higher severity. severity can be INFO, WARNING, MINOR, MAJOR or
                        CRITICAL
   --sort-order         Sort the results by ascending or descending time. Sort order can be asc or dsc
   --fetch-order        Fetch from end-time backwards or from start-time forward. Fetch order can be forward or
                        backward
   -H, --HOST           Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT           Specify the port. Alternatively, use the WEKA_PORT env variable
   --type-list          Include only events matches to the type_list, may appear more than once
   --category-list      Include only events matches to the category_list. Category can be Events, Node, Raid, Disk,
                        SSD, ObjectStorage, System, IO, Clustering, Statistics, Network, Filesystem, Upgrade, NFS,
                        Config, Cloud, InterfaceGroup or Custom
   --by-digested-time   Query and sort result by digested time
   --show-internal      Show internal events
   --server-timezone    Use the server's timezone instead of the local one
   -J, --json           Format output as JSON
```
