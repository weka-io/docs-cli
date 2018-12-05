```
Usage:
events list-local [--start-time <start>]
                  [--end-time <end>]
                  [--next next]
                  [--HOST HOST]
                  [--PORT PORT]
                  [--stem-mode]
                  [--show-internal]
                  [--server-timezone]
                  [--json]

Description:
    List recent events that happened on the machine running this command

Options:
   --start-time        Time of the beginning of the report period. Refer to the 'Datetime Switches Syntax' section in
                       'weka --help-syntax' for help regarding datetime typed switches
   --end-time          Time of the end of the report period. Refer to the 'Datetime Switches Syntax' section in 'weka
                       --help-syntax' for help regarding datetime typed switches
   --next              Token for the next page of events
   -H, --HOST          Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT          Specify the port. Alternatively, use the WEKA_PORT env variable
   --stem-mode         List stem mode events
   --show-internal     Show internal events
   --server-timezone   Use the server's timezone instead of the local one
   -J, --json          Format output as JSON
```
