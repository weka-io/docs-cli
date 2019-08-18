# Synopsis

```weka nfs permission add <filesystem>
                        <group>
                        [--path path]
                        [--permission-type permission-type]
                        [--HOST HOST]
                        [--PORT PORT]
                        [--json]```

# Description

Allow a client group to access a file system

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `filesystem` | File system name |
| `group` | Client group name |
| `--path` | path [default: /] |
| `--permission-type` | Permission type (format: 'ro' or 'rw') |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
