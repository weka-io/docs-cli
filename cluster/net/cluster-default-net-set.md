# Synopsis

```weka cluster default-net set [--range range]
                             [--gateway gateway]
                             [--netmask-bits netmask-bits]
                             [--HOST HOST]
                             [--PORT PORT]
                             [--json]
                             [--NO-HUMAN]```

# Description

Set the default data networking configuration

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>--range</pre> | IP range in the form of '1.2.3.4-8' |
| <pre>--gateway</pre> | Default gateway IP |
| <pre>--netmask-bits</pre> | Subnet mask bits (0..32) |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
