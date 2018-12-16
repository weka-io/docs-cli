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
| `-i, --dump-id` | Optional ID for this dump, if not specified a random ID is generated |
| `--timeout` | How many seconds to wait when downloading diags from remote servers. 0 means indefinite [default: 600] |
| `-o, --output` | Path to save generated summary file |
| `--pack-to` | Pack the collected tars into a single tarball under the given dir-path |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
