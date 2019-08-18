# Synopsis

```weka user ldap update [--server-uri server-uri]
                      [--base-dn base-dn]
                      [--user-object-class user-object-class]
                      [--user-id-attribute user-id-attribute]
                      [--group-object-class group-object-class]
                      [--group-membership-attribute group-membership-attribute]
                      [--group-id-attribute group-id-attribute]
                      [--reader-username reader-username]
                      [--reader-password reader-password]
                      [--admin-group admin-group]
                      [--regular-group regular-group]
                      [--readonly-group readonly-group]
                      [--start-tls start-tls]
                      [--certificate certificate]
                      [--ignore-start-tls-failure ignore-start-tls-failure]
                      [--server-timeout-secs server-timeout-secs]
                      [--protocol-version protocol-version]
                      [--user-signature-attribute user-signature-attribute]
                      [--HOST HOST]
                      [--PORT PORT]
                      [--json]```

# Description

Edit LDAP server configuration

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `--server-uri` | LDAP server URI ([ldap://]hostname[:port] or ldaps://hostname[:port]) |
| `--base-dn` | Base DN |
| `--user-object-class` | User object class |
| `--user-id-attribute` | User ID attribute |
| `--group-object-class` | Group object class |
| `--group-membership-attribute` | Group membership attribute |
| `--group-id-attribute` | Group ID attribute |
| `--reader-username` | Reader username |
| `--reader-password` | Reader password |
| `--admin-group` | Admin users group |
| `--regular-group` | Regular users group |
| `--readonly-group` | Readonly users group |
| `--start-tls` | Issue StartTLS after connecting (should not be used with ldaps://) (format: 'yes' or 'no') |
| `--certificate` | Certificate or certificate chain for the LDAP server |
| `--ignore-start-tls-failure` | Ignore certificate verification errors (format: 'yes' or 'no') |
| `--server-timeout-secs` | LDAP connection timeout in seconds |
| `--protocol-version` | LDAP protocol version |
| `--user-signature-attribute` | User signature attribute |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
