```
Usage:
cluster host cores <host-id>
                   <cores>
                   [--frontend-dedicated-cores frontend-dedicated-cores]
                   [--drives-dedicated-cores drives-dedicated-cores]
                   [--HOST HOST]
                   [--PORT PORT]
                   [--cores-ids cores-ids]...
                   [--json]
                   [--NO-HUMAN]

Description:
    Dedicate host's cores to weka

Arguments:
   host-id   Host ID as shown in `weka cluster host`
   cores     Number of CPU cores dedicated to weka - If set to 0 - no drive could be added to this host
Options:
   --frontend-dedicated-cores   Number of cores dedicated to weka frontend (out of the total <num-cores>)
   --drives-dedicated-cores     Number of cores dedicated to weka drives (out of the total <num-cores>)
   -H, --HOST                   Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT                   Specify the port. Alternatively, use the WEKA_PORT env variable
   --cores-ids                  Specify the ids of weka dedicated cores. 'cores ids type' param will be set to USER
   -J, --json                   Format output as JSON
   -N, --NO-HUMAN               Print sizes in Bytes. When not set, sizes are printed in human readable format, e.g
                                1KiB 234MiB 2GiB.
```
