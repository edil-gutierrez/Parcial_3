# Cofiguración de Ansible

## Primer paso, instalación de apache2 mendiante ansible.
```
ansible-playbook -i ../hosts webserver.yml
```
## Segundo paso, instalación de munin-node mendiante ansible.
```
ansible-playbook -i ../hosts munin-node.yml
```
## Tercer paso, instalación de munin mendiante ansible.
```
ansible-playbook -i ../hosts munin.yml
```
