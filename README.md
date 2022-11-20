# openvpn-deployment-using-ansible-roles-and-rundeck-gui
This repository contains three different ansible roles which deploys openvpn server, openvpn clients and revokes client's access from the server.
The ansible works in the background while rundeck acts as a frontend. I have created a project on a rundeck with three jobs which allows users to interact with a nice GUI to supply user inputs.
You should have installed and setup ansible and rundeck on your server to use above roles or you can also above roles directly via CLI.
Right now openvpn server deployment works on only CentOS7 OS. 
