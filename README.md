# Ansible Role: Defichain

An Ansible Role that installs a [Defichain Node / Masternode](https://github.com/defich/ain) on Linux

## Requirements

Any Linux based server would suffice with the following minimum specs:

| Type   | Value  |
| ------ | ------ |
| CPU    | 2 vCPU |
| Memory | 4 GB   |

## Role Variables

None.

## Dependencies

Ansible Role dependencies:

- [geerlingguy.swap](https://github.com/geerlingguy/ansible-role-swap)

## Example Playbook

```yaml
- hosts: all
  roles:
    - asyrafnorafandi.defichain
```

## License

MIT / BSD

## Author Information

This role was created in 2024 by [Asyraf Norafandi](https://www.github.com/asyrafnorafandi)
