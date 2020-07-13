# dev-machine

Runs [Ansible](https://docs.ansible.com/ansible/latest/index.html), provisioning local machine with dev tools and setup.

## Requires

Currently, [Ansible](https://docs.ansible.com/ansible/latest/index.html) and [Brew](https://brew.sh/). These will be automatically installed if missing.

## Usage

Run `./ansible.sh`. This will kick off the Ansible "playbook" (`playbook.yml`).

**WARNING**: This *will* install and modify packages on your machine. Read through the files in `roles/**/tasks/` so you know what will happen.

----

Cloned from [https://github.com/SteveEdson/dev-machine/](https://github.com/SteveEdson/dev-machine/)