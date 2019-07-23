# Synopsis

```weka smb cluster create <name>
                        <domain>
                        [--HOST HOST]
                        [--PORT PORT]
                        [--domain-netbios-name domain-netbios-name]
                        [--smb-conf-extra smb-conf-extra]
                        [--samba-hosts samba-hosts]...
                        [--smb-ips-pool smb-ips-pool]...
                        [--smb-ips-range smb-ips-range]...
                        [--json]```

# Description

Create a SMB cluster managed by weka

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `name` | The netbios name to give to the SMB cluster |
| `domain` | The domain to join the SMB cluster to |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--domain-netbios-name` | Custom domain netbios name in case it's not the first part of the domain name |
| `--smb-conf-extra` | Extra custom options to add to smb.conf |
| `--samba-hosts` | The hosts that will serve via the SMB protocol (pass weka's host id as a number) |
| `--smb-ips-pool` | IPs used as floating IPs for samba to server SMB in a HA manner. Then should not be assigned to any host on the network |
| `--smb-ips-range` | IPs used as floating IPs for samba to server SMB in a HA manner. Then should not be assigned to any host on the network (format: A.B.C.D-E, e.g. 1.2.3.4-8) |
| `-J, --json` | Format output as JSON |
