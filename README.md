# Setup

Debian Server with automation for repeatability
```
mkdir server_files && cd server_files
sudo apt update
sudo apt install -y ansible && git
sudo mkdir -p /etc/ansible
sudo touch /etc/ansible/hosts

git clone https://github.com/uvish/homeserver.git .

ansible-playbook ansible/debian_server.yml
```
