# Synopsis

```weka user ldap setup <server-uri>
                     <base-dn>
                     <user-object-class>
                     <user-id-attribute>
                     <group-object-class>
                     <group-membership-attribute>
                     <group-id-attribute>
                     <reader-username>
                     <reader-password>
                     [--cluster-admin-group cluster-admin-group]
                     [--org-admin-group org-admin-group]
                     [--regular-group regular-group]
                     [--readonly-group readonly-group]
                     [--start-tls start-tls]
                     [--ignore-start-tls-failure ignore-start-tls-failure]
                     [--server-timeout-secs server-timeout-secs]
                     [--protocol-version protocol-version]
                     [--user-signature-attribute user-signature-attribute]
                     [--HOST HOST]
                     [--PORT PORT]
                     [--json]```

# Description

Setup an LDAP server for user authentication

# Parameters

| Parameter | Description |
| --------- | ----------- |
| `server-uri` | LDAP server URI ([ldap://]hostname[:port] or ldaps://hostname[:port]) |
| `base-dn` | Base DN |
| `user-object-class` | User object class |
| `user-id-attribute` | User ID attribute |
| `group-object-class` | Group object class |
| `group-membership-attribute` | Group membership attribute |
| `group-id-attribute` | Group ID attribute |
| `reader-username` | Reader username |
| `reader-password` | Reader password |
| `--cluster-admin-group` | LDAP group of users that should get ClusterAdmin role (this role is only available for the root tenant to configure) |
| `--org-admin-group` | LDAP group of users that should get OrgAdmin role |
| `--regular-group` | LDAP group of users that should get Regular role |
| `--readonly-group` | LDAP group of users that should get ReadOnly role |
| `--start-tls` | Issue StartTLS after connecting (should not be used with ldaps://) (format: 'yes' or 'no') |
| `--ignore-start-tls-failure` | Ignore start TLS failure (format: 'yes' or 'no') |
| `--server-timeout-secs` | LDAP connection timeout in seconds |
| `--protocol-version` | LDAP protocol version |
| `--user-signature-attribute` | User signature attribute |
| `-H, --HOST` | Specify the host. Alternatively, use the WEKA_HOST env variable |
| `-P, --PORT` | Specify the port. Alternatively, use the WEKA_PORT env variable |
| `-J, --json` | Format output as JSON |
