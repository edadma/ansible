# ansible
This repo is intended to be pulled by `ansible-pull` to do a workstation setup. It works for Ubuntu 2020.

To setup a new workstation after a fresh OS install, start a terminal on the machine to be setup and do the following:

1) Install Ansible, and runtime dependencies: `sudo apt install ansible git python3-distutils`
2) Run `sudo ansible-pull -U https://github.com/edadma/ansible.git`
3) You should see `failed=0` somewhere in the last line of output.
