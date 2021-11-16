# Ansible Role: security_onion

Installs [Security Onion](https://github.com/Security-Onion-Solutions/securityonion).

## Requirements

- Ansible 2.10+
- Ubuntu >= 18.04
- CentOS >= 7

## Dependencies

None.

## Role Variables

```yaml
security_onion_git_version: "master"
```

## Configuration example

```yaml
- hosts: localhost
  name: so
  roles:
    - security_onion
```

## Licence

GPL-3.0

## Author information

Benjamin Akhras
