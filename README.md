Building Kubernetes over CentOS with Ansible
============================================

This is a small attempt to build Kubernetes with Ansible. I'm learning about both so is a practical experiment for me.

I test everything before push but if you find a typo, mistake or want to say something please go ahead.

I followed the Kubernetes over CentOS from the official page:

http://kubernetes.io/docs/getting-started-guides/centos/centos_manual_config/

I also tried to use as many env vars as I can. So take a look to vars/ dir in each role to fix your pretensions.

As usual for Ansible you need ssh access without password to all machines and each one have to resolve the others.

When your environment is ready:

`ansible-playbook -i inventory play.yaml`

## Otros Roles

ntp role by resmo/ansible-role-ntp forked from bennojoy/ntp

