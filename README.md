joenyland.dovecot
=================

[![CI](https://github.com/JoeNyland/ansible-dovecot-role/actions/workflows/ci.yml/badge.svg)](https://github.com/JoeNyland/ansible-dovecot-role/actions/workflows/ci.yml)

Installs [Dovecot](https://dovecot.org/).

Requirements
------------

None.

Role Variables
--------------

### `dovecot_mailbox_location`

Where Dovecot looks for user mailboxes.

### `dovecot_auth_username_format`

The format of the username to use when performing authenication.

### `dovecot_service_enabled`

Whether the Dovecot service should start at boot.

### `dovecot_service_state`

The state of the Dovecot service (e.g., `started` or `stopped`).

### `dovecot_ssl_cert`

Path to the SSL certificate file for Dovecot.

### `dovecot_ssl_key`

Path to the SSL key file for Dovecot.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: server
  roles:
    - joenyland.dovecot
```

License
-------

MIT

Author Information
------------------

⌨️ with ❤️ by [Joe Nyland](https://joe.nyland.io)
