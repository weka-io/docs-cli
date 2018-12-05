```
Usage:
alerts [--HOST HOST] [--PORT PORT] [--muted] [--json]

Description:
    List alerts in the Weka cluster

Subcommands:
   types    List all alert types that can be returned from the Weka cluster
   mute     Mute an alert-type. Muted alerts will not be prompted when listing active alerts. Alerts cannot be
            suppressed indefinitely, so a duration must be supplied. Once the supplied duration has passed, the
            alert-type would be automatically unmuted
   unmute   Unmute an alert-type which was previously muted.

Options:
   -H, --HOST   Specify the host. Alternatively, use the WEKA_HOST env variable
   -P, --PORT   Specify the port. Alternatively, use the WEKA_PORT env variable
   --muted      List muted alerts alongside the unmuted ones
   -J, --json   Format output as JSON
```
