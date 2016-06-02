# Overview
This role gets certificates signed by the Lets Encrypt CA for use by all TLS
connections. It sets up a recurring cron job to ensure that certificates are
renewed before they expire after 90 days of issuance.

# Dependencies
None

# Variables
```yaml
  - vars:
    domain: domain.com
    host_domains: domain.com, mail.domain.com
    admin_email: postmaster@domain.com
```
