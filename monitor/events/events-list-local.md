# Synopsis

```weka events list-local [--start-time <start>]
                       [--end-time <end>]
                       [--next next]
                       [--HOST HOST]
                       [--PORT PORT]
                       [--stem-mode]
                       [--show-internal]
                       [--server-timezone]
                       [--json]```

# Description

List recent events that happened on the machine running this command

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>--start-time</pre> | Time of the beginning of the report period. Refer to the 'Datetime Switches Syntax' section in 'weka --help-syntax' for help regarding datetime typed switches |
| <pre>--end-time</pre> | Time of the end of the report period. Refer to the 'Datetime Switches Syntax' section in 'weka --help-syntax' for help regarding datetime typed switches |
| <pre>--next</pre> | Token for the next page of events |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--stem-mode</pre> | List stem mode events |
| <pre>--show-internal</pre> | Show internal events |
| <pre>--server-timezone</pre> | Use the server's timezone instead of the local one |
| <pre>-J, --json</pre> | Format output as JSON |
