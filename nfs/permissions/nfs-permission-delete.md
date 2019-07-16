# Synopsis

```weka nfs permission delete <filesystem>
                           <group>
                           [--path path]
                           [--permission-type permission-type]
                           [--HOST HOST]
                           [--PORT PORT]
                           [--force]
                           [--json]```

# Description

Delete a file system permission

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `filesystem` | File system name |
| `group` | Client group name |
| `--path` | path [default: /] |
| `--permission-type` | Permission type (format: 'ro' or 'rw') |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-f, --force` | Force this action without further confirmation (this command may disrupt IO service for connected NFS clients and can be undone by re-creating the filesystem permission) |
| `-J, --json` | Format output as JSON |
