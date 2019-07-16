# Synopsis

```weka nfs permission update root-squashing <filesystem>
                                          <group>
                                          <anon-uid>
                                          <anon-gid>
                                          [--path path]
                                          [--permission-type permission-type]
                                          [--HOST HOST]
                                          [--PORT PORT]
                                          [--json]```

# Description

Edit a file system permission

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `filesystem` | File system name |
| `group` | Client group name |
| `anon-uid` | Anonymous UID to be used instead of root when root squashing is True |
| `anon-gid` | Anonymous GID to be used instead of root when root squashing is True |
| `--path` | path [default: /] |
| `--permission-type` | Permission type (format: 'ro' or 'rw') |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
