```
Usage:
version [--json]

Description:
    When run without arguments, lists the versions available on this machine. Subcommands allow for downloading of
    versions, setting the current version and other actions to manage versions.

Subcommands:
   supported-specs   List the Weka spec versions that are supported by this agent version
   get               Download a Weka version to the machine this command is executed from
   set               Set the current version. Containers must be stopped before setting the current version and the new
                     version must have already been downloaded.
   current           Prints the current version. If no version is set, a failure exit status is returned.
   rm                Delete a version from the machine this command is executed from
   prepare           Prepare the version for use. This includes things like compiling the version drivers for the local
                     machine.
   cleanup           Cleans up all traces of the specified version from the host, as though it was never run on it. It
                     doesn't remove the version's images, for that `weka version rm-version` should be used. WARNING -
                     This action is destructive and might cause a loss of data!

Options:
   -J, --json   Format output as JSON
```
