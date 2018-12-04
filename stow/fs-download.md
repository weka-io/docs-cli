```
Usage:
fs download <name>
            <group-name>
            <total-capacity>
            <ssd-capacity>
            <locator>
            [--max-files max-files]
            [--HOST HOST]
            [--PORT PORT]
            [--json]
            [--NO-HUMAN]

Description:
    Download a filesystem from object store

Arguments:
   name             Filesystem name
   group-name       Group name
   total-capacity   Total capacity [B|KiB|MiB|GiB|TiB|PiB|EiB|ZiB|YiB|KB|MB|GB|TB|PB|EB|ZB|YB]
   ssd-capacity     SSD capacity [B|KiB|MiB|GiB|TiB|PiB|EiB|ZiB|YiB|KB|MB|GB|TB|PB|EB|ZB|YB]
   locator          Locator
Options:
   --max-files      Max files
   -H, --HOST       Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT       Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json       Format output as JSON
   -N, --NO-HUMAN   Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB
                    2GiB.
```
