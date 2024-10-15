# IaC

## Requirements

```
ansible-galaxy collection install davidban77.gns3
sudo apt install sshpass
sudo apt-get -y install python-is-python3
```

```
ansible-playbook -vvv playbooks/deploy_network.yml --ask-pass
```

Review: https://github.com/bowlercbtlabs/Ansible-GNS3-Lab-Setup-part-2-Ansible-Install-and-Simple-Playbook-Execution-.git