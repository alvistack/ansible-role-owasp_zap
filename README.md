# Ansible Role for OWASP ZAP

<a href="https://alvistack.com" title="AlviStack" target="_blank"><img src="/alvistack.svg" height="75" alt="AlviStack"></a>

[![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/alvistack/ansible-role-owasp_zap/master)](https://gitlab.com/alvistack/ansible-role-owasp_zap/-/pipelines)
[![GitHub tag](https://img.shields.io/github/tag/alvistack/ansible-role-owasp_zap.svg)](https://github.com/alvistack/ansible-role-owasp_zap/tags)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-owasp_zap.svg)](https://github.com/alvistack/ansible-role-owasp_zap/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.owasp_zap-blue.svg)](https://galaxy.ansible.com/alvistack/owasp_zap)

Ansible Role for OWASP ZAP Installation.

## Requirements

This role require Ansible community package 4.10 or higher.

This role was designed for:

- Ubuntu 20.04, 22.04, 24.04, 24.10
- AlmaLinux 8, 9
- openSUSE Leap 15.5, 15.6, Tumbleweed
- Debian 11, 12, Testing
- Fedora 40, 41, Rawhide
- CentOS 7, 8 Stream, 9 Stream
- RHEL 7, 8, 9

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

## Example Playbook

[molecule/default/converge.yml](molecule/default/converge.yml)

This role could simply deploy to `localhost` as below:

    molecule converge -s default

## License

- Code released under [Apache License 2.0](LICENSE)
- Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

## Author Information

- Wong Hoi Sing Edison
  - <https://twitter.com/hswong3i>
  - <https://github.com/hswong3i>
