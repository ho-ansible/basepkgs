# Ansible role: basepkgs
Install standard set of software and remove unused packages.
Packages requiring configuration have their own roles.

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `stop_services`: services to stop/disable
+ `remove_pkgs`: packages to uninstall
+ `install_pkgs`: packages to install

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
