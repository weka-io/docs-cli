# Synopsis

```weka diags --collect [--dump-id dump-id]
                     [--timeout timeout]
                     [--output output]
                     [--pack-to pack-to]
                     [--HOST HOST]
                     [--PORT PORT]
                     [--json]```

# Description

Collect diags from all cluster hosts to a directory on the host running this command

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>-i, --dump-id</pre> | Optional ID for this dump, if not specified a random ID is generated |
| <pre>--timeout</pre> | How many seconds to wait when downloading diags from remote servers. 0 means indefinite [default: 600] |
| <pre>-o, --output</pre> | Path to save generated summary file |
| <pre>--pack-to</pre> | Pack the collected tars into a single tarball under the given dir-path |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
