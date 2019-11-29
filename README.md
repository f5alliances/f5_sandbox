# F5 AUTOMATION PROVISIONER

## Overview
The F5 Provisioner is a part of the automation sandbox. This is built by F5 Business Development organization.

## Goal
With F5 Automation provisioner, users are provided with an **F5 + Ansible** sandbox fully configured in the cloud. The provisioner can currently deploy infrastructure pieces in AWS 
- F5 BIG-IP
- Webservers
- Ansible node 
(More features will be added soon)

![f5 diagram](docs/images/f5topology.png)

Once the necessary infrastructure is deployed using the provisioner, users will be able to try out various automation scenarios using the use-case templates in the [f5alliances repo](https://github.com/f5alliances).

The Automation Sandbox can be used:
- as a self learning tool to get familiar with Ansible Automation for F5
- to build demos and proof of concepts
- to find automation solutions for common customer use-cases.

## How to use?
To get the Automation Sandbox setup there are two options:
1. Use the [Docker container](https://github.com/f5alliances/f5_provisioner/tree/master/docker) to provision the sandbox. This is the easiest way and therefore preferred.
2. Setup your own Linux distro and follow [F5 Ansible AWS Provisioner](https://github.com/f5alliances/f5_provisioner/blob/master/provisioner/README.md) for detailed steps to spin up and tear down the sandbox infrastructure using provisioner

## Next Step
Once you have setup the sandbox you can move forward and start with the [Ansible 101](https://github.com/f5alliances/ansible-use-cases-101) training.

## Support
This project is a community effort to promote Network and Security automation and is maintained by F5 BD. For any feature requests or issues, feel free to open an [issue](https://github.com/f5alliances/f5_provisioner/issues) and we will give our best effort to address it.
