# Synopsis

```weka events [--num-results num-results]
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
            [--json]```

# Description

List all events that conform to the filter criteria

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>-n, --num-results</pre> | Maximal number of results |
| <pre>--start-time</pre> | Include events occurred in this time point and later. Formatted like '2018-02-28T14:00:00' |
| <pre>--end-time</pre> | Include events occurred not later then this time point. Formatted like '2018-02-28T14:00:00' |
| <pre>--severity</pre> | Include event with equal and higher severity. severity can be INFO, WARNING, MINOR, MAJOR or CRITICAL |
| <pre>--sort-order</pre> | Sort the results by ascending or descending time. Sort order can be asc or dsc |
| <pre>--fetch-order</pre> | Fetch from end-time backwards or from start-time forward. Fetch order can be forward or backward |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--type-list</pre> | Include only events matches to the type_list, may appear more than once |
| <pre>--category-list</pre> | Include only events matches to the category_list. Category can be Events, Node, Raid, Disk, SSD, ObjectStorage, System, IO, Clustering, Statistics, Network, Filesystem, Upgrade, NFS, Config, Cloud, InterfaceGroup or Custom |
| <pre>--by-digested-time</pre> | Query and sort result by digested time |
| <pre>--show-internal</pre> | Show internal events |
| <pre>--server-timezone</pre> | Use the server's timezone instead of the local one |
| <pre>-J, --json</pre> | Format output as JSON |
