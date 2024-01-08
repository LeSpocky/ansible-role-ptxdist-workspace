# ptxdist workspace

Ansible Role for setting up a Debian host for working with
[PTXdist](https://www.ptxdist.org/) based Board Support Packages.

*Work in Progress*

## Requirements

*none*

## Role Variables

### Optional Variables

- `ptxws_apt_uri`:
    - Default: `"http://debian.pengutronix.de/debian/"`
    - Description: The debian package server URI.
      If you use an apt proxy, you can override this.

## Dependencies

*none*

## Example Playbook

### Minimal Example

```yaml
- name: Setup things on all workstations
  hosts: workstations

  roles:
    - ptxdist_workspace
```

### Full Example

```yaml
- name: Setup things on all workstations
  hosts: workstations

  roles:
    - role: ptxdist_workspace
      vars:
        ptxws_apt_uri: "http://approx.example.com:9999/pengutronix/"

```

## License

This project is licensed unter the [MIT License](LICENSES/MIT.txt)
unless noted differently in the file.

© 2024 [Alexander Dahl](https://github.com/LeSpocky) and contributors
