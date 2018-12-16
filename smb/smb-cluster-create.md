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
| <pre>workgroup</pre> | The workgroup to connect to |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--samba-hosts</pre> | The hosts that will serve via the SMB protocol (pass weka's host id as a number) |
| <pre>--smb-ips-pool</pre> | IPs used as floating IPs for samba to server SMB in a HA manner. Then should not be assigned to any host on the network |
| <pre>--smb-ips-range</pre> | IPs used as floating IPs for samba to server SMB in a HA manner. Then should not be assigned to any host on the network |
| <pre>-J, --json</pre> | Format output as JSON |
