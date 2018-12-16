# Synopsis

```weka nfs permission update <filesystem>
                           <group>
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
| <pre>filesystem</pre> | File system name |
| <pre>group</pre> | Client group name |
| <pre>--path</pre> | path [default: /] |
| <pre>--permission-type</pre> | Permission type, either RO (read only) or RW (read write) |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
