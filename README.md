<!--

---
lang: american
---
-->

[![Build Status](https://travis-ci.org/cw-ansible/cw.dell.svg?branch=master)](https://travis-ci.org/cw-ansible/cw.dell)
[![Tweet this](http://img.shields.io/badge/%20-Tweet-00aced.svg)](https://twitter.com/intent/tweet?tw_p=tweetbutton&via=renard_0&text=Install%20%23Dell%20%23OpenManage%20tools%20with%20%23Ansible)
[![Follow me on twitter](http://img.shields.io/badge/Twitter-Follow-00aced.svg)](https://twitter.com/intent/follow?region=follow_link&screen_name=renard_0&tw_p=followbutton)

# Install Dell OpenManage with ansible

This Ansible role install Dell *Open Manage* tools.

## Usage

This module is pretty straightforward, you only need to include it in your
playbook.

Note that this roles only runs if `ansible_system_vendor` claims to be a
Dell system.

## Description

This roles configures the Dell OpenManage apt directory and installs
`srvadmin-base`, `srvadmin-omcommon`.


## Configuration

- `dell_repository`: Source of the Dell apt repository. Change this only if
  you use a custom mirror (default:
  `http://linux.dell.com/repo/community/deb/latest`).


## Links

- [Dell OpenManage](http://linux.dell.com/repo/community/deb/latest/)


## Copyright

Author: Sébastien Gross `<seb•ɑƬ•chezwam•ɖɵʈ•org>` [@renard_0](https://twitter.com/renard_0)

License: WTFPL, grab your copy here: http://www.wtfpl.net

