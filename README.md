joenyland.dovecot
=================

[![CI](https://github.com/JoeNyland/ansible-dovecot-role/actions/workflows/ci.yml/badge.svg)](https://github.com/JoeNyland/ansible-dovecot-role/actions/workflows/ci.yml)

Installs [Dovecot](https://dovecot.org/).

Requirements
------------

None.

Role Variables
--------------

### `dovecot_mailbox_driver`

The mailbox driver to use.

### `dovecot_mailbox_path`

The path where user mailboxes are stored.

### `dovecot_inbox_path`

The path for the user's inbox. This is typically where incoming mail is delivered.

### `dovecot_auth_username_format`

The format of the username to use when performing authenication.

### `dovecot_service_enabled`

Whether the Dovecot service should start at boot.

### `dovecot_service_state`

The state of the Dovecot service (e.g., `started` or `stopped`).

### `dovecot_ssl_server_cert_file`

Path to the SSL certificate file for Dovecot.

### `dovecot_ssl_server_key_file`

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
