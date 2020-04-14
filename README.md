# ansible-role-copy.etc_issue

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

This role was created in 2020 by Graham Lillico.
