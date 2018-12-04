# Table of contents

## General

* [Get Syntax Information](general/--help-syntax.md)
* [Get CLI Build Number](general/--build.md)
* [Get CLI Version](general/--version.md)
* [Get CLI Version](general/-v.md)
* [Show Help](general/-h.md)
* [Show Help](general/--help.md)
* [Show Legal Information](general/--legal.md)
* [Cluster Status](general/status.md)
* [Rebuild Status](general/status-rebuild.md)

## Cluster

* [Cluster Commands](cluster/cluster.md)
* [Create Cluster](cluster/cluster-create.md)
* [Set Cluster Parameters](cluster/cluster-update.md)
* [List Nodes](cluster/cluster-nodes.md)
* [List Failure Domains](cluster/cluster-failure-domain.md)
* [Set Hot Spares](cluster/cluster-hot-spare.md)
* [Start IO Service](cluster/cluster-start-io.md)
* [Stop IO Service](cluster/cluster-stop-io.md)
* [List Drives](cluster/cluster-drive.md)
* [Scan Drives](cluster/cluster-drive-scan.md)
* [Activate Drives](cluster/cluster-drive-activate.md)
* [Deactivate Drives](cluster/cluster-drive-deactivate.md)
* [Add Drive](cluster/cluster-drive-add.md)
* [List Hosts](cluster/cluster-host.md)
* [Show Host Hardware](cluster/cluster-host-info-hw.md)
* [Show Hardware Information](cluster/cluster-host-info-config.md)
* [Set Host Failure Domain](cluster/cluster-host-failure-domain.md)
* [Dedicate Hosts](cluster/cluster-host-dedicate.md)
* [Get/Set Host Bandwidth](cluster/cluster-host-bandwidth.md)
* [Set Host Cores](cluster/cluster-host-cores.md)
* [Set Host RAM](cluster/cluster-host-memory.md)
* [Activate Hosts](cluster/cluster-host-activate.md)
* [Deactivate Hosts](cluster/cluster-host-deactivate.md)
* [Add Host](cluster/cluster-host-add.md)
* [Remove Host](cluster/cluster-host-remove.md)
* [Host Factory Reset](cluster/cluster-host-factory-reset.md)
* [List Host NICs](cluster/cluster-host-net.md)
* [Add Host NIC](cluster/cluster-host-net-add.md)
* [Remove Host NIC](cluster/cluster-host-net-remove.md)
* [Show Default Data Network](cluster/cluster-default-net.md)
* [Set Default Data Network](cluster/cluster-default-net-set.md)
* [Reset Default Data Network](cluster/cluster-default-net-reset.md)

## Filesystem

* [List Filesystems](filesystem/fs.md)
* [Create Filesystem](filesystem/fs-create.md)
* [Update Filesystem](filesystem/fs-update.md)
* [Delete Filesystem](filesystem/fs-delete.md)
* [List Filesystem Groups](filesystem/fs-group.md)
* [Create Filesystem Group](filesystem/fs-group-create.md)
* [Update Filesystem Group](filesystem/fs-group-update.md)
* [Delete Filesystem Group](filesystem/fs-group-delete.md)

## Snapshots

* [Restore Filesystem](snapshots/fs-restore.md)
* [List Snapshots](snapshots/fs-snapshot.md)
* [Create Snapshot](snapshots/fs-snapshot-create.md)
* [Copy Snapshot](snapshots/fs-snapshot-copy.md)
* [Update Snapshot](snapshots/fs-snapshot-update.md)
* [Delete Snapshot](snapshots/fs-snapshot-delete.md)

## Tiering

* [Show Tiering Status](tiering/fs-tier.md)
* [Get File Tiering Status](tiering/fs-tier-location.md)
* [Fetch Tiered File](tiering/fs-tier-fetch.md)
* [List S3 Object Stores](tiering/fs-tier-s3.md)
* [Add S3 Object Store](tiering/fs-tier-s3-add.md)
* [Update S3 Object Store](tiering/fs-tier-s3-update.md)
* [Delete S3 Object Store](tiering/fs-tier-s3-delete.md)

## STOW

* [Download Filesystem](stow/fs-download.md)
* [Upload Snapshot](stow/fs-snapshot-upload.md)

## NFS

* [NFS Commands](nfs/nfs.md)
* [NFS Rules Commands](nfs/nfs-rules.md)
* [NFS Rules Adding](nfs/nfs-rules-add.md)
* [Adding DNS Rule](nfs/nfs-rules-add-dns.md)
* [Adding IP Rule](nfs/nfs-rules-add-ip.md)
* [NFS Rules Deleting](nfs/nfs-rules-delete.md)
* [Delete DNS Rule](nfs/nfs-rules-delete-dns.md)
* [Delete IP Rule](nfs/nfs-rules-delete-ip.md)
* [List NFS Client Groups](nfs/nfs-client-group.md)
* [Create NFS Client Group](nfs/nfs-client-group-add.md)
* [Delete NFS Client Group](nfs/nfs-client-group-delete.md)
* [List NFS Permissions](nfs/nfs-permission.md)
* [Add Filesystem Permission](nfs/nfs-permission-add.md)
* [Add Filesystem Permission With Root Squashing](nfs/nfs-permission-add-root-squashing.md)
* [Update Filesystem Permission With Root Squashing](nfs/nfs-permission-update-root-squashing.md)
* [Update Filesystem Permission](nfs/nfs-permission-update.md)
* [Delete Filesystem Permission](nfs/nfs-permission-delete.md)
* [List Interface Groups](nfs/nfs-interface-group.md)
* [List Interface Group Assignment](nfs/nfs-interface-group-assignment.md)
* [Create Interface Group](nfs/nfs-interface-group-add.md)
* [Update Interface Group](nfs/nfs-interface-group-update.md)
* [Delete Interface Group](nfs/nfs-interface-group-delete.md)
* [IP Range Commands](nfs/nfs-interface-group-ip-range.md)
* [Add IP Range](nfs/nfs-interface-group-ip-range-add.md)
* [Delete IP Range](nfs/nfs-interface-group-ip-range-delete.md)
* [NFS Interface Group Port Commands](nfs/nfs-interface-group-port.md)
* [Add Port To Interface Group](nfs/nfs-interface-group-port-add.md)
* [Remove Port From Interface Group](nfs/nfs-interface-group-port-delete.md)

## SMB

* [SMB Commands](smb/smb.md)
* [Show SMB Status](smb/smb-cluster.md)
* [Create SMB Cluster](smb/smb-cluster-create.md)
* [Destroy SMB Cluster](smb/smb-cluster-destroy.md)
* [List Shares](smb/smb-share.md)
* [Add Share](smb/smb-share-add.md)
* [Remove Share](smb/smb-share-remove.md)
* [Change Share Owner](smb/smb-share-chown.md)
* [List Users](smb/smb-user.md)
* [Add User](smb/smb-user-add.md)
* [Remove User](smb/smb-user-remove.md)

## Alerts

* [List Alerts](alerts/alerts.md)
* [List Alert Types](alerts/alerts-types.md)
* [Mute Alert Type](alerts/alerts-mute.md)
* [Unmute Alert Type](alerts/alerts-unmute.md)

## Events

* [Start Agent Daemon](events/--agent.md)
* [Cloud Commands](events/cloud.md)
* [Cloud Status](events/cloud-status.md)
* [Enable Cloud](events/cloud-enable.md)
* [Disable Cloud](events/cloud-disable.md)
* [Update Cloud Settings](events/cloud-update.md)
* [Cloud Credentials Commands](events/cloud-creds.md)
* [Refresh Cloud Credentials](events/cloud-creds-refresh.md)
* [Get Cloud Upload Rate](events/cloud-upload-rate.md)
* [Set Cloud Upload Rate](events/cloud-upload-rate-set.md)
* [Get UI URL](events/cloud-ui.md)
* [Set UI URL](events/cloud-ui-set.md)
* [List Events](events/events.md)
* [List Local Events](events/events-list-local.md)
* [List Event Types](events/events-list-types.md)

## Stats

* [Get Stats](stats/stats.md)
* [Get Realtime Stats](stats/stats-realtime.md)
* [List Stats Types](stats/stats-list-types.md)

## Diags

* [Diagnostics Commands](diags/diags.md)
* [Collect Diagnostics](diags/diags---collect.md)
* [Upload Diagnostics](diags/diags---upload.md)

## Users

* [List Users](users/user.md)
* [Login](users/user-login.md)
* [Show Current User](users/user-whoami.md)
* [Change Password](users/user-passwd.md)
* [Create User](users/user-add.md)
* [Delete User](users/user-delete.md)

## Licensing

* [Show License Status](licensing/cluster-license.md)
* [Enable PAYG](licensing/cluster-license-payg.md)
* [Reset License](licensing/cluster-license-reset.md)
* [Install License](licensing/cluster-license-set.md)

## Mount

* [Mount a Filesystem](mount/mount.md)
* [Unmount a Filesystem](mount/umount.md)

## Local

* [Agent Commands](local/agent.md)
* [Install Agent](local/agent-install-agent.md)
* [Install Agent](local/local-install-agent.md)
* [Update Containers Format](local/agent-update-containers.md)
* [List Supported Specs](local/agent-supported-specs.md)
* [Cleanup Images](local/agent-cleanup-images.md)
* [Uninstall Agent](local/agent-uninstall.md)
* [Local Commands](local/local.md)
* [List Containers](local/local-ps.md)
* [Setup Container](local/local-setup.md)
* [Delete Container](local/local-rm.md)
* [Start Container](local/local-start.md)
* [Stop Container](local/local-stop.md)
* [Restart Container](local/local-restart.md)
* [Show Container Status](local/local-status.md)
* [Enable Monitoring](local/local-enable.md)
* [Disable Monitoring](local/local-disable.md)
* [Turn Monitoring On/Off](local/local-monitoring.md)
* [Collect Diagnostics](local/local-diags.md)
* [Run Command In Existing Container](local/local-exec.md)
* [Run Command In New Container](local/local-run.md)
* [List Supported Specs](local/version-supported-specs.md)
* [List Installed Versions](local/version.md)
* [Download Version](local/version-get.md)
* [Set Current Version](local/version-set.md)
* [Get Current Version](local/version-current.md)
* [Delete Version](local/version-rm.md)
* [Prepare Version](local/version-prepare.md)
* [Cleanup Version](local/version-cleanup.md)
