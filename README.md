ansible-tailscale
=========

Install and run Tailscale client.

Requirements
------------

Debian family distribution

Role Variables
--------------

| Variable                       | Required | type   | Comments                           |
|--------------------------------|----------|--------|------------------------------------|
| tailscale_debian_keyrepository | yes      | list   | Key repositories for debian family |
| tailscale_debian_repository    | yes      | list   | Repositories for debian family     |
| tailscale_pkg                  | yes      | string | Tailscake pkg name                 |
| tailscale_preauthkey           | no       | string | Tailscale pre auth key             |
| tailscale_up                   | yes      | string | Tailscale up arguments             |

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.


Add in your playbooks requirements
----------------

```yaml
- src: https://github.com/enzops/ansible-tailscale
  name: enzops.tailscale
  version: latest
```

License
-------

MIT

Author Information
------------------

[github.com/enzops](https://github.com/enzops)
