```
Usage:
agent 

Description:
    Command s that control the weka agent (outside the weka containers)

Subcommands:
   install-agent       Installs WekaIO agent on the machine the command is executed from
   update-containers   Update the currently available containers and version specs to the current agent version. This
                       command does not update weka, only the container's representation on the local machine.
   supported-specs     List the Weka spec versions that are supported by this agent version
   cleanup-images      Remove any remaining images that are no longer needed
   uninstall           Deletes all Weka files, drivers, shared memory and any other remainder from the machine this
                       command is executed from. WARNING - This action is destructive and might cause a loss of data!

```
