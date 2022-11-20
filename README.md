# Openvpn Server deployment using ansible roles and rundeck GUI
This repository contains three different ansible roles which deploy openvpn server, openvpn clients and revokes client's access from the server.
The ansible works in the background while rundeck acts as a frontend. I have created a project on a rundeck with three jobs which allows users to interact with a nice GUI to supply user inputs.
You can directly use and run above roles with CLI from the ansible server but if you like to have GUI, then you can use Rundeck with ansible to have that feature.
Right now openvpn server deployment job works with CentOS7 VM only from any cloud provider like AWS, Digital Ocean, Linode etc but it does not support any other OS except CentOS7.

### 1. Ansible
It is an open source automation tool that automates provisioning, configuration management, application deployment, orchestration, and many other IT processes. More details from [here](https://www.ansible.com/).

### 2. Rundeck
It is an open source automation tool with a Graphical USer Interface (GUI), Command Line Interface (CLI) and a WebAPI. It helps to deploy automation tasks across a set of nodes. More details from [here](https://www.rundeck.com/).
### 3. Some screenshots of openvpn rundeck deployoment jobs
###### Rundeck Login Console
![rundeck-console](https://user-images.githubusercontent.com/11027110/202899800-3b5239af-8a4a-4a13-870a-8eb1d7a56cd5.jpg)
###### Rundeck Jobs for OpenVPN Server
![rundeck-job-history](https://user-images.githubusercontent.com/11027110/202899534-c4277ef3-f722-4d60-97ae-b6e7011ea05f.jpg)
###### Rundeck User Input form for OpenVPN Server Deployment
![deploy-openvpn-server](https://user-images.githubusercontent.com/11027110/202899620-7aee6a2e-3c42-4a3e-978f-a44ea54a507d.jpg)
