# Install_ansible.sh 
#!/bin/bash
sudo apt update
sudo apt install software-properties-cammon
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible -y
