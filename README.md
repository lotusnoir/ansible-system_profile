# ansible-system_profile

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_profile-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_profile)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_profile.svg)](https://github.com/lotusnoir/ansible-system_profile/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_profile?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_profile)
[![downloads](https://img.shields.io/ansible/role/d/56943)](https://galaxy.ansible.com/lotusnoir/system_profile)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56943)](https://galaxy.ansible.com/lotusnoir/system_profile)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Configure profile for users

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_profile
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_profile


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

