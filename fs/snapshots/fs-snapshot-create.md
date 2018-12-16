# Synopsis

```weka fs snapshot create <file-system>
                        <name>
                        <access-point>
                        [--source-snapshot source-snapshot]
                        [--HOST HOST]
                        [--PORT PORT]
                        [--is-writable]
                        [--json]
                        [--NO-HUMAN]```

# Description

Create a snapshot

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>file-system</pre> | Source Filesystem name |
| <pre>name</pre> | Target Snapshot name |
| <pre>access-point</pre> | Access point |
| <pre>--source-snapshot</pre> | Source snapshot |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--is-writable</pre> | Writable |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
