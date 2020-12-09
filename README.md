# Ansible Role : copy_etc_issue

[![CI](https://github.com/glillico/ansible-role-copy_etc_issue/workflows/CI/badge.svg)](https://github.com/glillico/ansible-role-copy_etc_issue/actions?query=workflow%3ACI)

This role copies the text file 'files/etc/issue' to '/etc/issue' on the server.

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - glillico.configure_sshd

## License

MIT

## Author Information

Created in 2020 by Graham Lillico.
