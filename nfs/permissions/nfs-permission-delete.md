```
Usage:
nfs permission delete <filesystem>
                      <group>
                      [--path path]
                      [--permission-type permission-type]
                      [--HOST HOST]
                      [--PORT PORT]
                      [--json]

Description:
    Delete a file system permission

Arguments:
   filesystem   File system name
   group        Client group name
Options:
   --path              path [default: /]
   --permission-type   Permission type, either RO (read only) or RW (read write)
   -H, --HOST          Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT          Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json          Format output as JSON
```
