# jtprog.configure_timesyncd

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprog/ansible-role-configure-timesyncd/CI?label=CI) ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprog/ansible-role-configure-timesyncd/Release?label=Release) ![GitHub](https://img.shields.io/github/license/jtprog/ansible-role-configure-timesyncd)


Общая роль для настройки systemd-timesyncd

Переменные:
```yaml
timedatectl_timeservers: ['0.debian.pool.ntp.org',
                        '1.debian.pool.ntp.org',
                        '2.debian.pool.ntp.org',
                        '3.debian.pool.ntp.org']

timedatectl_timeservers_fallback: ['0.debian.pool.ntp.org',
                        '1.debian.pool.ntp.org',
                        '2.debian.pool.ntp.org',
                        '3.debian.pool.ntp.org']

timedatectl_timezone: Europe/Moscow
```
