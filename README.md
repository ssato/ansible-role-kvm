ssato.kvm_host
=================

*ssato.kvm_host* is an ansible role to setup KVM host, just does a few things actually.

- Install KVM related packages if not there
- Ensure KVM kernel modules are loaded with Nested KVM feature is enabled if the hardware supports it.

[![Build Status](https://travis-ci.org/ssato/ansible-role-kvm_host.svg?branch=master)](https://travis-ci.org/ssato/ansible-role-kvm_host)


Requirements
------------

### Software

- Python2.6+, I guess.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

```yml
- hosts: kvm_hosts
  roles:
     - role: ssato.kvm_host
```

License
-------
MIT


Author
-------

*Satoru SATOH* [ssato@Github](https://github.com/ssato)

