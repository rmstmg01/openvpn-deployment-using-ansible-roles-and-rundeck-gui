# Openvpn Server deployment using ansible roles and rundeck gui
This repository contains three different ansible roles which deploys openvpn server, openvpn clients and revokes client's access from the server.
The ansible works in the background while rundeck acts as a frontend. I have created a project on a rundeck with three jobs which allows users to interact with a nice GUI to supply user inputs.
You should have installed and setup ansible and rundeck on your server to use above roles or you can also above roles directly via CLI.
Right now openvpn server deployment works on only CentOS7 OS. 

### 1. Ansible
It is an open source automation tool that automates provisioning, configuration management, application deployment, orchestration, and many other IT processes. More details from [here](https://www.ansible.com/).

### 2. Rundeck
It is an open source automation tool with a Graphical USer Interface (GUI), Command Line Interface (CLI) and a WebAPI. It helps to deploy automation tasks across a set of nodes. More details from [here](https://www.rundeck.com/).
### 3. Some screenshots of openvpn rundeck deployoment jobs
###### Rundeck Login Console
![rundeck-console](https://user-images.githubusercontent.com/11027110/202899181-d335eded-33db-4634-be03-2c6658118a63.jpg)
###### Rundeck Jobs for OpenVPN Server
![rundeck-job-history](https://user-images.githubusercontent.com/11027110/202899534-c4277ef3-f722-4d60-97ae-b6e7011ea05f.jpg)
###### Rundeck User Input form for OpenVPN Server Deployment
![deploy-openvpn-server](https://user-images.githubusercontent.com/11027110/202899620-7aee6a2e-3c42-4a3e-978f-a44ea54a507d.jpg)
