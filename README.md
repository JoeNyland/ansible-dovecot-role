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
