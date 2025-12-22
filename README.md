# Ansible role: basepkgs
Install standard set of software and remove unused packages.
Packages requiring configuration have their own roles.

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `services_stop` (default: empty): services to stop/disable
+ `pkgs_remove` (default: empty): packages to uninstall
+ `pkgs_install_*`: list of packages to install

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
