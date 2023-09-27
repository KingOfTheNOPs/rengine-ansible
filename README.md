# rengine-ansible
Using ansible to automate the configuration and deployment of a host running rengine 

## Install Dependencies
Assuming ansible is already installed
```
ansible-galaxy collection install community.docker
```

## Usage

```
ansible-playbook site-rengine.yaml -i inventory.yaml
```