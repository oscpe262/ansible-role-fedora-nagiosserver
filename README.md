# Ansible role 'ansible-role-fedora-nagiosserver'

An Ansible role for setting up Nagios Core on Fedora 26 or later.
This role does not support SELinux for now.
Thanks to https://www.hiroom2.com/2017/07/12/fedora-26-nagios-en/ for inspiration.

## Requirements
Fedora 26 or later

## Role Variables
| Variable		| Default		| Comments (type) |
| :---			| :---			| :---		  |
| nagios_password | none | A password is required to pass, preferably through a vault file |

## Dependencies

## Example Playbook
```Yaml
- hosts: foo
  roles:
    - role: ansible-role-fedora-nagiosserver
```

## Testing


## License

BSD

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Please create a topic branch for your proposed changes, it's the easiest way to merge back into the project.

- [Oscar Petersson](https://github.com/oscpe262/) (Maintainer)
