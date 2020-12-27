# ansible

My ansible playbooks to set up my computer.

## Setup

```shell
# Clone the repo
sudo apt install -y git
git clone git@github.com:Hasnep/ansible.git

# Install ansible
sudo apt install -y python3 python3-pip python3-venv
python3 -m venv ~/.venvs/ansible
~/.venvs/ansible/bin/python -m pip install ansible

# Run playbooks
~/.venvs/ansible/bin/ansible-playbook *.yml 
```
