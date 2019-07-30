# Synopsis

```weka smb domain join <username>
                     <password>
                     [--server server]
                     [--create-computer create-computer]
                     [--extra-options extra-options]
                     [--HOST HOST]
                     [--PORT PORT]
                     [--json]```

# Description

Join cluster to Active Directory domain

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `username` | The name of the administrator user to join the domain using it |
| `password` | The administrator user password |
| `--server` | The domain controller server |
| `--create-computer` | Precreate the computer account in a specific OU |
| `--extra-options` | Consult with Samba's 'net ads join' manual for extra options |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
