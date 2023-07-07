# snap-ansible

## Add Snaps to Ubuntu or Debian Workstation

### Debian prerequisites

If you are using Debian, perform installation steps at [debian-ansible](https://github.com/lab1702/debian-ansible) first.

### Ansible Commands

Run this to apply the config to your workstation after making sure snapd is working:

    sudo ansible-pull -U https://github.com/lab1702/snap-ansible.git
