# Ansible tests

## Installation instructions (including Azure integration)

```shell
python3 -m venv venv
source venv/bin/activate
pip install ansible
ansible-galaxy collection install azure.azcollection --force
pip install -r ~/.ansible/collections/ansible_collections/azure/azcollection/requirements-azure.txt
```
