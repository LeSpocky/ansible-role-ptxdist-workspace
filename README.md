# ptxdist workspace

Ansible Role for setting up a Debian host for working with
[PTXdist](https://www.ptxdist.org/) based Board Support Packages.

*Work in Progress*

## Requirements

*none*

## Role Variables

*none*

## Dependencies

*none*

## Example Playbook

```yaml
- name: Setup things on all workstations
  hosts: workstations

  roles:
    - ptxdist_workspace
```

## License

This project is licensed unter the [MIT License](LICENSES/MIT.txt)
unless noted differently in the file.

© 2024 [Alexander Dahl](https://github.com/LeSpocky) and contributors
