# ansible
This repo is intended to be pulled in by `ansible-pull` to setup a workstation. It works for Ubuntu 2019/2020.

To setup a new workstation after a fresh OS install (it assumes there's exactly one unprivileged user), start a terminal on the machine to be setup and do the following:

1) Install Ansible, and runtime dependencies: `sudo apt install ansible git python3-distutils`
2) Run `sudo ansible-pull -U https://github.com/edadma/ansible.git`
3) You should see `failed=0` somewhere in the last line of output, showing that there were no failures in executing any of the tasks.

Several debug messages are output to provide some post installation information.
