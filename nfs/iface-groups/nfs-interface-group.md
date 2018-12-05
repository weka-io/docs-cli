```
Usage:
nfs interface-group [--name name] [--HOST HOST] [--PORT PORT] [--json]

Description:
    List interface groups

Subcommands:
   assignment   List the currently assigned interface for each floating-IP address in the given interface-group. If
                <name> is not supplied, assignments for all floating-IP addresses will be listed
   add          Create an interface group
   update       Update an interface group
   delete       Delete an interface group
   ip-range     Commands that manage nfs interface-groups' ip-ranges
   port         Commands that manage nfs interface-groups' ports

Options:
   --name       Group name
   -H, --HOST   Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT   Specify the port. Alternatively, use the WEKA_PORT env variable
   -J, --json   Format output as JSON
```
