# Ansible Setup

This is my ansible setup for reproducing my programming/linux environment anywhere.

This is still quite early in development, but to get started, make sure that you run `pacman -Syu` and make sure you have sudo privileges enabled.

**DO NOT** run `ansible-playbook` with sudo! If you do, some actions will be performed in the root user's home directory, such as cloning git repos.

Use this command to run your playbook:

``` shell
ansible-playbook arch.yml
```
