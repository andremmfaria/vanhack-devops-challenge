# Ansible -> EC2 -> Wordpress
Deploy fresh instance of Wordpress on EC2 instance using Ansible playbooks

Please remember about setting these environmental variables for AWS authentication (or use boto config):
* AWS_ACCESS_KEY_ID
* AWS_SECRET_ACCESS_KEY
 
Don't forget about changing your keypair and security groups as these are currently not generated automatically. 

How to run: ```ansible-playbook --private-key="~/.ssh/your_key.pem" site.yml ```