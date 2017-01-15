# Ansible for Azure deployments

Updated for Ansible 2.2
This templates deploy VMs in Public Azure
- playbook : winarm - deploy nano server in Public Azure using ARM and json template
- playbook:  winclassic - deploy CentOS 7 in Public Azure Classic

Require: pip install "azure==2.0.0rc5”


In additionally playbook: winrm allows to communicate with Windows Machine on Azure
Require: require pip install "pywinrm"

To Customize:
- inventory/hosts
- template.json

