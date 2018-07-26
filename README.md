## netcat

[![Build Status](https://travis-ci.org/Oefenweb/ansible-netcat.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-netcat) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-netcat-blue.svg)](https://galaxy.ansible.com/Oefenweb/netcat)

Set up netcat in Debian-like systems.

#### Requirements

* `netcat-traditional` (will be installed)

#### Variables

None

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - netcat
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-netcat/issues)!
