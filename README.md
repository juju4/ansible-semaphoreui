[![Actions Status - Master](https://github.com/juju4/ansible-semaphoreui/workflows/AnsibleCI/badge.svg)](https://github.com/juju4/ansible-semaphoreui/actions?query=branch%3Amaster)
[![Actions Status - Devel](https://github.com/juju4/ansible-semaphoreui/workflows/AnsibleCI/badge.svg?branch=devel)](https://github.com/juju4/ansible-semaphoreui/actions?query=branch%3Adevel)

# semaphoreui ansible role

Setup [Semaphoreui](https://github.com/semaphoreui/semaphore/) with ansible

## Requirements & Dependencies

### Ansible
It was tested on the following versions:
 * 2.17

### Operating systems

Tested on Ubuntu 24.04, 22.04, 20.04, Centos/Rockylinux 9.

## Example Playbook

Just include this role in your list.
For example

```
- host: myhost
  roles:
    - juju4.semaphoreui
```

you probably want to review variables

## Variables

TBD

## Continuous integration

```
$ pip install molecule docker
$ molecule test
$ MOLECULE_DISTRO=ubuntu:24.04 molecule test --destroy=never
```

## Troubleshooting & Known issues

TBD

## License

BSD 2-clause
