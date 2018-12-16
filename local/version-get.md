# Synopsis

```weka version get <version> [--from from]... [--set-current] [--no-progress-bar]```

# Description

Download a Weka version to the machine this command is executed from

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>version</pre> | Version to download |
| <pre>--from</pre> | Also try downloading from this distribution server (can be given multiple times). Distribution servers are taken from the $WEKA_DIST_SERVERS environment variable and the /etc/wekaio/dist-servers file. |
| <pre>--set-current</pre> | Set the downloaded version as the current version. Will fail if any containers are currently running. |
| <pre>--no-progress-bar</pre> | Don't render download progress bar |
