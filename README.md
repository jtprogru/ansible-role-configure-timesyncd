# jtprogru.configure_timesyncd

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-configure-timesyncd/CI?label=CI)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-configure-timesyncd/Release?label=Release)
![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-configure-timesyncd)
[![Ansible Role](https://img.shields.io/ansible/role/53230)](https://galaxy.ansible.com/jtprogru/configure_timesyncd/)
[![GitHub tag](https://img.shields.io/github/tag/jtprogru/ansible-role-configure-timesyncd.svg)](https://github.com/jtprogru/ansible-role-configure-timesyncd/tags)

Simple role for configure systemd-timesyncd

## Role Variables

See [`defaults/main.yml`](defaults/main.yml).

## Example Playbook

Example playbook:
```yaml
---
- name: Configure TimeSyncD
  hosts: all
  become: true
  gather_facts: true
  roles:
    - jtprogru.configure_timesyncd
```

## Author

Michael Savin aka [@jtprogru](https://github.com/jtprogru)

## License

See [LICENSE](LICENSE.md)

