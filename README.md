# rke2-deploy
Ansible playbook to deploy rke2 cluster

# Features
- Automated Deployment: Deploy a multi-node RKE2 cluster using Ansible.
- Customizable: Easily configure cluster settings.
- Scalable: Suitable for both small and large scale deployments.

# Prerequisites
- Ansible
- Python
- Target nodes (at least one master)
- SSH Access to the target nodes

# Configuration
- Inventory File: Edit 'hosts' file to include your target nodes. Specify which nodes will be master and which will be worker nodes. Remember to specify the hostname or DNS name of the target nodes in the inventory file. This configuration will set all master nodes as control-plane + etcd roles
- Playbook: Edit 'rke2-install.yaml' if you want to make any change in the Playbook.

# More info
First ansible proyect, so feel free to contribute or correct me in order to improve my knowledge
