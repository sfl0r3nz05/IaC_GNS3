# DevSecOps for Infrastructure As Code

## Prerequisites

Ansible 2.9 or higher
GNS3 2.2 or higher
GNS3 VM running and accessible

```console
ansible-galaxy collection install davidban77.gns3
sudo apt install sshpass
sudo apt-get -y install python-is-python3
```

## Project Structure

```console
.
├── ansible.cfg
├── group_vars
│   └── all.yml
├── inventory
│   └── hosts.yml
├── playbooks
│   └── deploy_network.yml
└── README.md
```

## Deployment

```
ansible-playbook -vvv playbooks/deploy_network.yml --ask-pass
```

## Current status of automatic deployment of Spine-leaf architecture

![alt text](documentation/actual_net.png)


## Troubleshooting

1. Add different ports to OpenPLC docker.

## To Do

1. Improve architecture 
1. Improve architecture:
    a. [Add Digital Twin](https://github.com/borgestassio/Wind-Turbine-Control)
    b. Test Codesys PLC
2. Add security layer
3. Add automation layer
