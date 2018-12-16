# Synopsis

```weka stats [--start-time <start>]
           [--end-time <end>]
           [--interval interval]
           [--resolution-secs <secs>]
           [--HOST HOST]
           [--PORT PORT]
           [--category category]...
           [--stat stat]...
           [--node-ids node-ids]...
           [--param <key:val>]...
           [--accumulated]
           [--per-node]
           [--no-zeroes]
           [--show-internal]
           [--server-timezone]
           [--json]```

# Description

List all statistics that conform to the filter criteria

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>--start-time</pre> | Time of the beginning of the report period. Refer to the 'Datetime Switches Syntax' section in 'weka --help-syntax' for help regarding datetime typed switches |
| <pre>--end-time</pre> | Time of the beginning of the report period. Refer to the 'Datetime Switches Syntax' section in 'weka --help-syntax' for help regarding datetime typed switches |
| <pre>--interval</pre> | Period (in seconds) of time of the report |
| <pre>--resolution-secs</pre> | Length of each interval in the report period |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--category</pre> | Retrieve only statistics of the specified categories |
| <pre>--stat</pre> | Retrieve only the specified statistics |
| <pre>--node-ids</pre> | Limit the report to the specified nodes |
| <pre>--param</pre> | For parameterized statistics, retrieve only the instantiations where the specified parameter is of the specified value. Multiple values can be supplied for the same key, e.g. '--param method:putBlocks --param method:initBlock'. Refer to the 'Key-Value Switches Syntax' section in 'weka --help-syntax' for help regarding key-value typed switches |
| <pre>--accumulated</pre> | Show accumulated statistics, not rate statistics |
| <pre>--per-node</pre> | Do not aggregate statistics across nodes |
| <pre>--no-zeroes</pre> | Do not retrieve results where the value is 0 |
| <pre>--show-internal</pre> | Show internal statistics |
| <pre>--server-timezone</pre> | Use the server's timezone instead of the local one |
| <pre>-J, --json</pre> | Format output as JSON |
