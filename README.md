# ec2-playbook
An Ansible EC2 Playbook for hosting applications on AWS
## Instructions
1. Install Python3: `sudo apt-get install python3`
2. Install required dependencies: `python3 -m pip install -r ansible-requirements.txt`
3. Copy AWS credentials to `~/.aws/credentials`
4. Run the playbook: `ansible-playbook -v site.yml`
