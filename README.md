# ansible-stig-rhel7

Ansible role for RHEL7 STIG.

The goal is for this role to find and fix any STIG related findings for RHEL7.

## Getting Started

Assuming you have Vagrant installed you can use the following to
test the role

```
$ git clone https://github.com/inspec-stigs/inspec-stig-rhel7.git
$ cd inspec-stig-rhel7
$ pip install -r requirements.txt
$ vagrant up --no-provision
$ vagrant provision
```
