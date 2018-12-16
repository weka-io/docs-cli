# Synopsis

```weka smb cluster create <workgroup>
                        [--HOST HOST]
                        [--PORT PORT]
                        [--samba-hosts samba-hosts]...
                        [--smb-ips-pool smb-ips-pool]...
                        [--smb-ips-range smb-ips-range]...
                        [--json]```

# Description

Create a SMB cluster managed by weka

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `workgroup` | The workgroup to connect to |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--samba-hosts` | The hosts that will serve via the SMB protocol (pass weka's host id as a number) |
| `--smb-ips-pool` | IPs used as floating IPs for samba to server SMB in a HA manner. Then should not be assigned to any host on the network |
| `--smb-ips-range` | IPs used as floating IPs for samba to server SMB in a HA manner. Then should not be assigned to any host on the network |
| `-J, --json` | Format output as JSON |
