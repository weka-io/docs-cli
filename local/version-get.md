# Synopsis

```weka version get <version> [--from from]... [--set-current] [--no-progress-bar]```

# Description

Download a Weka version to the machine this command is executed from

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `version` | Version to download |
| `--from` | Also try downloading from this distribution server (can be given multiple times). Distribution servers are taken from the $WEKA_DIST_SERVERS environment variable and the /etc/wekaio/dist-servers file. |
| `--set-current` | Set the downloaded version as the current version. Will fail if any containers are currently running. |
| `--no-progress-bar` | Don't render download progress bar |
