# ansible

Pre-requisite
1. Create 3 GCE in GCP & make 1 GCE as controller and other 2 GCE as Client
2. In controller install Ansible 2.5.5
3. In Client machines, the requirement is to install the apache server with specific configuration file and Index.html files


Create Below artifacts in the controller machine to configure the target machines through playbook


inventory - This folder contains the yaml file which has all the target machine's address like IP and Port, etc
Playbook - Any yaml file that is there in the root folder is consider as play book.
role - 