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
| <pre>filesystem</pre> | File system name |
| <pre>group</pre> | Client group name |
| <pre>permission-type</pre> | Permission type, either RO (read only) or RW (read write) |
| <pre>anon-uid</pre> | Anonymous UID to be used instead of root when root squashing is True |
| <pre>anon-gid</pre> | Anonymous GID to be used instead of root when root squashing is True |
| <pre>--path</pre> | path [default: /] |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>-J, --json</pre> | Format output as JSON |
