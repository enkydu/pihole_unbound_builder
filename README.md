# Pi-hole & Unbound Ansible Builder

Ansible playbook for initial installation and configuration of Pi-hole and Unbound on Raspberry Pi. 

This script will install Pi-hole and Unbound on your RaspberryPi. You have to provide variables for this script:

**host_ip** - IP of your RaspberryPi where you want to install Pi-hole & Unbound  
**pi_pwd** - password for your "pi" user on RaspberryPi. If you are using different user, change username in hosts file

These variables are set via .passwds.yml ansible-vault file with ansible-vault password provided via file .vault_pass. 

***.passwds.yml template***

    host_ip: <xxx.xxx.xxx.xxx>
    pi_pwd: <your_password>
