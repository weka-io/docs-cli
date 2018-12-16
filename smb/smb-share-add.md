# Synopsis

```weka smb share add <share-name>
                   <fs-name>
                   [--description description]
                   [--internal-path internal-path]
                   [--mount-option mount-option]
                   [--HOST HOST]
                   [--PORT PORT]
                   [--share-option share-option]...
                   [--json]```

# Description

Add a new share to be exposed by samba

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>share-name</pre> | The name of the share being added |
| <pre>fs-name</pre> | Filesystem name to share |
| <pre>--description</pre> | A description for samba to show regarding the share |
| <pre>--internal-path</pre> | The path inside the filesystem to share |
| <pre>-o, --mount-option</pre> | Option to pass to the mount command when mounting weka |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--share-option</pre> | Additional options to pass on to samba. NOTE - This parameter is DANGEROUS, use with caution. Incorect usage may lead to DATA LOSS. |
| <pre>-J, --json</pre> | Format output as JSON |
