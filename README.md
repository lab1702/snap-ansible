# snap-ansible

## Add Snaps to Debian or Ubuntu Workstation

### Debian prerequisites

If you are using Debian, perform installation steps at [debian-ansible](https://github.com/lab1702/debian-ansible) first.

### Ansible Commands

Run this to apply the config to your workstation after making sure snapd is working:

    sudo ansible-pull -U https://github.com/lab1702/snap-ansible.git

## Install Go packages for editor support

Run this to install language server, debugger and linter:

    go install golang.org/x/tools/gopls@latest
    go install github.com/go-delve/delve/cmd/dlv@latest
    go install honnef.co/go/tools/cmd/staticcheck@latest
