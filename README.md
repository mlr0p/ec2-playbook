# ec2-playbook
An Ansible EC2 Playbook for hosting applications on AWS
## Instructions
1. Install Python3 and pip: `sudo apt-get install python3 python3-pip`
2. Install required dependencies: `python3 -m pip install -r ansible-requirements.txt`
3. Reboot the machine: `reboot`
3. Copy AWS credentials to `~/.aws/credentials`
4. To provision the EC2 instance and deploy webserver: `ansible-playbook -v webservers.yml`
5. To terminate the EC2 instance: `ansible-playbook -v terminate_ec2.yml`
