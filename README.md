# tools
RPW - Rapid Setup Workstation

Prepare Workstation
Read the ubuntu.yml file before applying and be sure to understand everything that will be done.

1- Install Ansible
sudo apt update && sudo apt install ansible unzip git -y

2- Clone this repository
git clone https://github.com/caiodelgadonew/tools.git

3- Apply the configuration
ansible-playbook tools/ubuntu.yml --ask-become-pass

*Type your password when asked to give root permissions for some actions.

