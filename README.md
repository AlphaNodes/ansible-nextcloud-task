# Ansible Role: nextcloud-task

Run console task for nextcloud on Debian / Ubuntu.

At the moment only cron is supported.

## Installation

### Ansible 2+

Using ansible galaxy cli:

```bash
ansible-galaxy install alphanodes.nextcloud-task
```

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

## Dependencies

Installed nextcloud.

## Example Playbook

```yaml
- hosts: server-name
  vars:
    nextcloud_task_name: cron
  roles:
    - AlphaNodes.nextcloud-task
```

## License

GPL Version 3

## Author Information

This role was created in 2022 by [AlphaNodes](https://alphanodes.com/).
