# Synopsis

```weka version rm [--all-non-used] [--force] [<version-name>]...```

# Description

Delete a version from the machine this command is executed from

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `version-name` | The versions to remove |
| `--all-non-used` | Delete all versions which aren't the current set version for any of the containers |
| `-f, --force` | Force this action without further confirmation (this command deletes the version and would not allow running this version without downloading it again) |
