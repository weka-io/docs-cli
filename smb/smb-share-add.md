# Synopsis

```weka smb share add <share-name>
                   <fs-name>
                   [--description description]
                   [--internal-path internal-path]
                   [--file-create-mask file-create-mask]
                   [--directory-create-mask directory-create-mask]
                   [--mount-option mount-option]
                   [--HOST HOST]
                   [--PORT PORT]
                   [--share-option share-option]...
                   [--acl]
                   [--json]```

# Description

Add a new share to be exposed by samba

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `share-name` | The name of the share being added |
| `fs-name` | Filesystem name to share |
| `--description` | A description for samba to show regarding the share |
| `--internal-path` | The path inside the filesystem to share |
| `--file-create-mask` | POSIX mode mask files will be created with. E.g. "0744" |
| `--directory-create-mask` | POSIX mode mask directories will be created with. E.g. "0755" |
| `-o, --mount-option` | Option to pass to the mount command when mounting weka. NOTE - This parameter is DANGEROUS, use with caution. Incorrect usage may lead to DATA LOSS. |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--share-option` | Additional options to pass on to samba. NOTE - This parameter is DANGEROUS, use with caution. Incorrect usage may lead to DATA LOSS. |
| `--acl` | EXPERIMENTAL! Enable Windows ACLs on the share. Will also be translated (as possible) to POSIX ACLs. |
| `-J, --json` | Format output as JSON |
