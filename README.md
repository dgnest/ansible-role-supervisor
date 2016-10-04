# Ansible Role Supervisor

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/dgnest/ansible-role-supervisor.svg)](https://travis-ci.org/dgnest/ansible-role-supervisor)
[![GitHub issues](https://img.shields.io/github/issues/dgnest/ansible-role-supervisor.svg)](https://github.com/dgnest/ansible-role-supervisor/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [supervisor][link-supervisor] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - [Homebrew][link-brew] must be installed.


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for supervisor


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: servers
      roles:
         - supervisor

To install a specific version:

    - hosts: servers
      roles:
         - { role: dgnest.supervisor }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-author]
- [All Contributors][link-contributors]

[link-supervisor]: https://supervisord.org/
[link-brew]: http://brew.sh/

<!-- Other -->

[link-author]: https://github.com/luismayta
[link-contributors]: AUTHORS
