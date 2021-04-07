# Ansible-playbook

### Install Docker on VM/Baremetal 

**Command:**

`ansible-playbook ./Install_docker_on_machine/docker_playbook.yml -i ./machine_hosts/hosts.yml --extra-vars "host=vm1_hostname,vm2_hostname" --extra-vars "ssh_user=root" --extra-vars="USER=user_to_add_in_docker_group"`

### Create a new user on VM/Baremetal

**Command**

`ansible-playbook ./create_new_user_on_machine/create_new_user.yml -i ./machine_hosts/hosts.yml --extra-vars "host=vm1_hostname,vm2_hostname"`
