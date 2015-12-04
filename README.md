# Ansible Role - kjtanaka.epel [![Build Status][travis-image]][travis-url]

This role installs EPEL repository on CentOS box.

## Usage

Install the role with ansible-galaxy:

```bash
ansible-galaxy install kjtanaka.epel
```

Include the role like this:

```yaml
- hosts: servers
  roles:
    - { role: kjtanaka.epel }
```

## License

MIT License

## Author

Koji Tanaka - RDI2

[travis-url]: https://travis-ci.org/kjtanaka/ansible-role-epel
[travis-image]: https://travis-ci.org/kjtanaka/ansible-role-epel.svg?branch=master
