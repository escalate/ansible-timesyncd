# Ansible Role: systemd-timesyncd

[![CI](https://github.com/escalate/ansible-raspberry-systemd-timesyncd/workflows/CI/badge.svg?event=push)](https://github.com/escalate/ansible-raspberry-systemd-timesyncd/actions?query=workflow%3ACI)

An Ansible role that manages [systemd-timesyncd](https://www.freedesktop.org/software/systemd/man/systemd-timesyncd.service.html) on Raspberry Pi OS.

## Install

```
$ ansible-galaxy install escalate.raspberry-systemd-timesyncd
```

## Role Variables

Please see [defaults/main.yml](https://github.com/escalate/ansible-raspberry-systemd-timesyncd/blob/master/defaults/main.yml) for a complete list of variables that can be overridden.

## Dependencies

This role relies on the following dependencies:

* Roles: None
* Collections: [collections.yml](https://github.com/escalate/ansible-raspberry-systemd-timesyncd/blob/master/collections.yml)

## Example Playbook

```
- hosts: all
  roles:
    - role: escalate.raspberry-systemd-timesyncd
      tags: timesyncd
```

## License

MIT
