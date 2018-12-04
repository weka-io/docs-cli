```
Usage:
local setup <type> [--name name] [--depends-on depends-on]... [--disable] [--start] [--remove-on-boot]

Description:
    Setup a local weka container

Arguments:
   type   The type of the container to create
Options:
   --name             The name to give the container
   --depends-on       Mark the container as depending on the given containers
   --disable          Should the container be created as disabled
   --start            Should the container be started after creation
   --remove-on-boot   Should the container be removed when this machine is rebooted
```
