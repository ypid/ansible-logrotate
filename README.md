## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) logrotate

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](http://img.shields.io/travis/debops/ansible-logrotate.svg?style=flat)](http://travis-ci.org/debops/ansible-logrotate)
[![test-suite](http://img.shields.io/badge/test--suite-ansible--logrotate-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-logrotate/)
[![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.logrotate-660198.svg?style=flat)](https://galaxy.ansible.com/debops/logrotate/)


The `logrotate` package is used to periodically rotate logs, so that they
don't fill up the disk space on the filesystem. Rotated logs can be moved to
a different host or emailed before removal for archival purposes.

The `debops.logrotate` Ansible role allows you to manage log rotation
configuration for system packages, or create custom log configuration. The role
can be used by other roles as a dependency to make automatic `logrotate`
configuration easier.

### Installation

This role requires at least Ansible `v2.0.0`. To install it, run:

```Shell
ansible-galaxy install debops.logrotate
```

### Documentation

More information about `debops.logrotate` can be found in the
[official debops.logrotate documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-logrotate/docs/).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`logrotate` role was written by:

- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
