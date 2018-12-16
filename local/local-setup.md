# Synopsis

```weka local setup <type> [--name name] [--depends-on depends-on]... [--disable] [--start] [--remove-on-boot]```

# Description

Setup a local weka container

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>type</pre> | The type of the container to create |
| <pre>--name</pre> | The name to give the container |
| <pre>--depends-on</pre> | Mark the container as depending on the given containers |
| <pre>--disable</pre> | Should the container be created as disabled |
| <pre>--start</pre> | Should the container be started after creation |
| <pre>--remove-on-boot</pre> | Should the container be removed when this machine is rebooted |
