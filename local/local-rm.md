# Synopsis

```weka local rm [--all] [--force] [<containers>]...```

# Description

Delete a Weka container from the machine this command is executed from (without removing it's images)

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `containers` | The containers to remove |
| `--all` | Remove all containers |
| `-f, --force` | Force this action without further confirmation (this command is destructive and cannot be undone) |
