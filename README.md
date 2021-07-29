# ageres210784/vmalert

An Ansible role which installs and configures [vmalert] on Linux

## Requirements

Ansible 2.8+

## Role Variables

You can see all vars in `defaults/main.yml` vars file.

## Dependencies

None

## Example Playbook

```yaml
- name: Ensure prometheus_alertmanager DB
  hosts: vmalerts
  remote_user: root

  roles:
    - ageres210784.vmalert
```

## License

Apache 2.0

## Author Information

This role was created by [Sergey Evseev].
