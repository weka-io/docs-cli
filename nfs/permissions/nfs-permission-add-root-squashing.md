# Synopsis

```weka nfs permission add root-squashing <filesystem>
                                       <group>
                                       <permission-type>
                                       <anon-uid>
                                       <anon-gid>
                                       [--path path]
                                       [--HOST HOST]
                                       [--PORT PORT]
                                       [--json]```

# Description

Add a file system permission with root-squashing

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `filesystem` | File system name |
| `group` | Client group name |
| `permission-type` | Permission type, either RO (read only) or RW (read write) |
| `anon-uid` | Anonymous UID to be used instead of root when root squashing is True |
| `anon-gid` | Anonymous GID to be used instead of root when root squashing is True |
| `--path` | path [default: /] |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
