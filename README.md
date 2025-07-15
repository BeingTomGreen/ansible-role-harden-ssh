# beingtomgreen.harden_ssh

A simple Ansible role to harden ssh.

## Installation

Given that Galaxy seems to have abandoned roles, I suggest referencing this repository directly in your projects `requirements.yml`:

```yml
---

roles:
  - name: beingtomgreen.harden_ssh
    src: https://github.com/BeingTomGreen/ansible-role-harden-ssh.git

collections: []
```

You can then install the requirements as normal:

```bash
ansible-galaxy install -r requirements.yml
```

## Requirements

None.

## Role Variables

See [defaults/main.yml](defaults/main.yml) and [vars/main.yml](defaults/main.yml).

## Dependencies

None.

## Example Playbook

```yml
- hosts: all
  roles:
    - beingtomgreen.harden_ssh
```

## License

[MIT](LICENSE)

## Author Information

[Tom Green](https://github.com/BeingTomGreen)
