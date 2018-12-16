# Synopsis

```weka cluster host net add <host-id>
                          [--device device]
                          [--ips-type ips-type]
                          [--ips ips]
                          [--gateway gateway]
                          [--netmask netmask]
                          [--name name]
                          [--HOST HOST]
                          [--PORT PORT]
                          [--bond-devices bond-devices]...
                          [--json]
                          [--NO-HUMAN]```

# Description

Allocate a dedicated networking device on a host (to the cluster).

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | The host's id |
| `--device` | Network device pci-slot/mac-address/interface-name(s) |
| `--ips-type` | IPs type: POOL: IPs from the default data networking IP pool would be used, USER: configured by the user |
| `--ips` | IPs to be allocated to cores using the device. If not given - IPs may be set automatically according the interface's IPs, or taken from the default networking IPs pool |
| `--gateway` | Default gateway IP. In AWS this value is auto-detected, otherwise the default data networking gateway will be used. |
| `--netmask` | Netmask in bits number. In AWS this value is auto-detected, otherwise the default data networking netmask will be used. |
| `--name` | If empty, a name will be auto generated. |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--bond-devices` | Alternative to device - A bond of several network devices, specified as a comma separated list. |
| `-J, --json` | Format output as JSON |
| `-N, --NO-HUMAN` | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
