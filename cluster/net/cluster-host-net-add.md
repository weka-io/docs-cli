# Synopsis

```weka cluster host net add <host-id>
                          [--device device]
                          [--ips-type ips-type]
                          [--gateway gateway]
                          [--netmask netmask]
                          [--name name]
                          [--HOST HOST]
                          [--PORT PORT]
                          [--bond-devices bond-devices]...
                          [--ips ips]...
                          [--json]
                          [--raw-units]
                          [--UTC]```

# Description

Allocate a dedicated networking device on a host (to the cluster).

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `host-id` | The host's id |
| `--device` | Network device pci-slot/mac-address/interface-name(s) |
| `--ips-type` | IPs type: POOL: IPs from the default data networking IP pool would be used, USER: configured by the user (format: 'pool' or 'user') |
| `--gateway` | Default gateway IP. In AWS this value is auto-detected, otherwise the default data networking gateway will be used. |
| `--netmask` | Netmask in bits number. In AWS this value is auto-detected, otherwise the default data networking netmask will be used. |
| `--name` | If empty, a name will be auto generated. |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `--bond-devices` | This option is no longer supported |
| `--ips` | IPs to be allocated to cores using the device. If not given - IPs may be set automatically according the interface's IPs, or taken from the default networking IPs pool (format: A.B.C.D-E, e.g. 1.2.3.4-8) |
| `-J, --json` | Format output as JSON |
| `-R, --raw-units` | Print values in raw units (bytes, seconds, etc.). When not set, sizes are printed in human-readable format, e.g 1KiB 234MiB 2GiB. |
| `-U, --UTC` | Print times in UTC. When not set, times are converted to the local time of this host. |
