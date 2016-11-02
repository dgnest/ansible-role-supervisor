# Ansible Role Supervisor

<span class="badges" align="center">
[![GitHub tag](https://img.shields.io/github/tag/dgnest/ansible-role-supervisor.svg?maxAge=2592000)](https://github.com/dgnest/ansible-role-supervisor)
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

Made with :heart: ️:coffee:️ and :pizza: by [dgnest][link-company].

- [All Contributors][link-contributors]

[link-supervisor]: https://supervisord.org/
[link-brew]: http://brew.sh/

<!-- Other -->

[link-company]: https://github.com/dgnest
[link-contributors]: AUTHORS
