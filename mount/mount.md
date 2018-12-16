# Synopsis

```weka mount <source> <target> [--option option] [--type type] [--no-mtab] [--sloppy] [--fake] [--verbose]```

# Description

Mounts a wekafs filesystem. This is the helper utility installed at /sbin/mount.wekafs.

# Parameters

| Parameter | Description |
| --------- | ----------- |
| <pre>source</pre> | Source filesystem to mount |
| <pre>target</pre> | Location to mount the source filesystem on |
| <pre>-o, --option</pre> | Mount options |
| <pre>-t, --type</pre> | The filesystem type |
| <pre>-n, --no-mtab</pre> | Mount without writing in /etc/mtab. This is necessary for example when /etc is on a read-only filesystem |
| <pre>-s, --sloppy</pre> | Tolerate sloppy mount options rather than failing |
| <pre>-f, --fake</pre> | Causes everything to be done except for the actual system call |
| <pre>-v, --verbose</pre> | Verbose mode |
