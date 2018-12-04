```
Usage:
smb share add <share-name>
              <fs-name>
              [--description description]
              [--internal-path internal-path]
              [--mount-option mount-option]
              [--HOST HOST]
              [--PORT PORT]
              [--share-option share-option]...
              [--json]

Description:
    Add a new share to be exposed by samba

Arguments:
   share-name   The name of the share being added
   fs-name      Filesystem name to share
Options:
   --description        A description for samba to show regarding the share
   --internal-path      The path inside the filesystem to share
   -o, --mount-option   Option to pass to the mount command when mounting weka
   -H, --HOST           Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT           Specify the port. Alternatively, use the WEKA_PORT env variable
   --share-option       Additional options to pass on to samba. NOTE - This parameter is DANGEROUS, use with caution.
                        Incorect usage may lead to DATA LOSS.
   -J, --json           Format output as JSON
```
