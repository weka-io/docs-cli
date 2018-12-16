# Synopsis

```weka umount <target> [--type type] [--verbose] [--no-mtab] [--lazy-unmount] [--force] [--readonly]```

# Description

Unmounts wekafs filesystems. This is the helper utility installed at /sbin/umount.wekafs.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>target</pre> | The target mount point to unmount |
| <pre>-t, --type</pre> | Indicate that the actions should only be taken on file systems of the specified type |
| <pre>-v, --verbose</pre> | Verbose mode |
| <pre>-n, --no-mtab</pre> | Unmount without writing in /etc/mtab |
| <pre>-l, --lazy-unmount</pre> | Detach the filesystem from the filesystem hierarchy now, and cleanup all references to the filesystem as soon as it is not busy anymore |
| <pre>-f, --force</pre> | Force unmount |
| <pre>-r, --readonly</pre> | In case unmounting fails, try to remount read-only |
