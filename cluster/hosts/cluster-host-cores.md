# Synopsis

```weka cluster host cores <host-id>
                        <cores>
                        [--frontend-dedicated-cores frontend-dedicated-cores]
                        [--drives-dedicated-cores drives-dedicated-cores]
                        [--HOST HOST]
                        [--PORT PORT]
                        [--cores-ids cores-ids]...
                        [--json]
                        [--NO-HUMAN]```

# Description

Dedicate host's cores to weka

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>host-id</pre> | Host ID as shown in `weka cluster host` |
| <pre>cores</pre> | Number of CPU cores dedicated to weka - If set to 0 - no drive could be added to this host |
| <pre>--frontend-dedicated-cores</pre> | Number of cores dedicated to weka frontend (out of the total <num-cores>) |
| <pre>--drives-dedicated-cores</pre> | Number of cores dedicated to weka drives (out of the total <num-cores>) |
| <pre>-H, --HOST</pre> | Specify the host. Alternatively, use the WEKA_HOST env variable |
| <pre>-P, --PORT</pre> | Specify the port. Alternatively, use the WEKA_PORT env variable |
| <pre>--cores-ids</pre> | Specify the ids of weka dedicated cores. 'cores ids type' param will be set to USER |
| <pre>-J, --json</pre> | Format output as JSON |
| <pre>-N, --NO-HUMAN</pre> | Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g 1KiB 234MiB 2GiB. |
