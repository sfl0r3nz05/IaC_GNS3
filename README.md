# IaC

## Requirements

```
ansible-galaxy collection install davidban77.gns3
sudo apt install sshpass
sudo apt-get -y install python-is-python3
```

## Deployment

```
ansible-playbook -vvv playbooks/deploy_network.yml --ask-pass
```

## Current status

![alt text](documentation/status.png)
