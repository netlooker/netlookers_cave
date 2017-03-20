# Setting up Environment based on CodeAnywhere
The easiest that I've found is to use CodeAnywhere empty container and run the Ansible provisioning script.

Follow those commands to set up ansible in the empty container:
> ```
> sudo apt-get update
> sudo apt-get install software-properties-common 
> sudo apt-add-repository ppa:ansible/ansible
> sudo apt-get update
> sudo apt-get install ansible
> ```

