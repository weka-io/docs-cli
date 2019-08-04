# Synopsis

```weka nfs permission update <filesystem>
                           <group>
                           [--path path]
                           [--permission-type permission-type]
                           [--root-squashing root-squashing]
                           [--anon-uid anon-uid]
                           [--anon-gid anon-gid]
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
| `--path` | path [default: /] |
| `--permission-type` | Permission type (format: 'ro' or 'rw') |
| `--root-squashing` | Root squashing (format: 'on' or 'off') |
| `--anon-uid` | Anonymous UID to be used instead of root when root squashing is enabled |
| `--anon-gid` | Anonymous GID to be used instead of root when root squashing is enabled |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
