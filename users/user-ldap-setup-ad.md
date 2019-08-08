# Synopsis

```weka user ldap setup-ad <server-uri>
                        <domain>
                        <reader-username>
                        <reader-password>
                        <admin-group>
                        <regular-group>
                        <readonly-group>
                        [--start-tls start-tls]
                        [--ignore-start-tls-failure ignore-start-tls-failure]
                        [--server-timeout-secs server-timeout-secs]
                        [--HOST HOST]
                        [--PORT PORT]
                        [--json]```

# Description

Setup an Active Directory server for user authentication

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `server-uri` | LDAP server URI ([ldap://]hostname[:port] or ldaps://hostname[:port]) |
| `domain` | Domain |
| `reader-username` | Reader username |
| `reader-password` | Reader password |
| `admin-group` | Admin users group |
| `regular-group` | Regular users group |
| `readonly-group` | Readonly users group |
| `--start-tls` | Issue StartTLS after connecting (should not be used with ldaps://) (format: 'yes' or 'no') |
| `--ignore-start-tls-failure` | Ignore start TLS failure (format: 'yes' or 'no') |
| `--server-timeout-secs` | LDAP connection timeout in seconds |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
