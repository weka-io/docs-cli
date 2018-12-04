```
Usage:
stats [--start-time <start>]
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
      [--json]

Description:
    List all statistics that conform to the filter criteria

Subcommands:
   realtime     Get performance related stats which are updated in a one-second interval.
   list-types   Show the statistics definition information

Options:
   --start-time        Time of the beginning of the report period. Refer to the 'Datetime Switches Syntax' section in
                       'weka --help-syntax' for help regarding datetime typed switches
   --end-time          Time of the beginning of the report period. Refer to the 'Datetime Switches Syntax' section in
                       'weka --help-syntax' for help regarding datetime typed switches
   --interval          Period (in seconds) of time of the report
   --resolution-secs   Length of each interval in the report period
   -H, --HOST          Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT          Specify the port. Alternatively, use the WEKA_PORT env variable
   --category          Retrieve only statistics of the specified categories
   --stat              Retrieve only the specified statistics
   --node-ids          Limit the report to the specified nodes
   --param             For parameterized statistics, retrieve only the instantiations where the specified parameter is
                       of the specified value. Multiple values can be supplied for the same key, e.g. '--param
                       method:putBlocks --param method:initBlock'. Refer to the 'Key-Value Switches Syntax' section in
                       'weka --help-syntax' for help regarding key-value typed switches
   --accumulated       Show accumulated statistics, not rate statistics
   --per-node          Do not aggregate statistics across nodes
   --no-zeroes         Do not retrieve results where the value is 0
   --show-internal     Show internal statistics
   --server-timezone   Use the server's timezone instead of the local one
   -J, --json          Format output as JSON
```
