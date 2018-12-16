# Synopsis

```weka umount <target> [--type type] [--verbose] [--no-mtab] [--lazy-unmount] [--force] [--readonly]```

# Description

Unmounts wekafs filesystems. This is the helper utility installed at /sbin/umount.wekafs.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `target` | The target mount point to unmount |
| `-t, --type` | Indicate that the actions should only be taken on file systems of the specified type |
| `-v, --verbose` | Verbose mode |
| `-n, --no-mtab` | Unmount without writing in /etc/mtab |
| `-l, --lazy-unmount` | Detach the filesystem from the filesystem hierarchy now, and cleanup all references to the filesystem as soon as it is not busy anymore |
| `-f, --force` | Force unmount |
| `-r, --readonly` | In case unmounting fails, try to remount read-only |
