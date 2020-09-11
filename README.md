# Jenkins-in-ubuntu-18-using-ansible-in-ec2-machine

Ansible playbook to install a Jenkins server using ssh Target OS: Ubuntu 18 

Command for execute playbook:

ansible-playbook -i <inventory file name> ansible-install-jenkins-ubuntu18.yml

You will need to configuree the host "<Your intansce ip add>" ,key-pair for ssh with your target server credentials in inevntory file under test-server group.
