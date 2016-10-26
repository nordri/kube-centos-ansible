Kubernetes sobre CentOS con Ansible
===================================

Este repo está en fase beta. Se ha seguido la guía de CentOS en la documentación oficial de Kubernetes para automatizar el despliegue.

http://kubernetes.io/docs/getting-started-guides/centos/centos_manual_config/

Se utilizan los nombres de maquina que sugiere la guia.

Para utilizarlo preparar una máquina CentOS de master y otras maquinas CentOS como workers. 

Cuando esté todo listo

ansible-playbook -i inventory play.yaml

## Otros Roles

ntp role by resmo/ansible-role-ntp forked from bennojoy/ntp

