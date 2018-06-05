# Ansible role: basepkgs
Install standard set of software and remove unused packages.

## Requirements
Only tested on Debian stable, for now.

## Role Variables

## Dependencies
None.

## Example Playbook

```
- hosts: all
  roles:
    - { role: ho-ansible.basepkgs }
```

## License
MIT

## Author Information
Sean Ho, https://github.com/ho-ansible/
