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
| <pre>host-id</pre> | The host's id |
| <pre>--device</pre> | Network device pci-slot/mac-address/interface-name(s) |
| <pre>--ips-type</pre> | IPs type: POOL: IPs from the default data networking IP pool would be used, USER: configured by the user |
| <pre>--ips</pre> | IPs to be allocated to cores using the device. If not given - IPs may be set automatically according the interface's IPs, or taken from the default networking IPs pool |
| <pre>--gateway</pre> | Default gateway IP. In AWS this value is auto-detected, otherwise the default data networking gateway will be used. |
| <pre>--netmask</pre> | Netmask in bits number. In AWS this value is auto-detected, otherwise the default data networking netmask will be used. |
| <pre>--name</pre> | If empty, a name will be auto generated. |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--bond-devices</pre> | Alternative to device - A bond of several network devices, specified as a comma separated list. |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
