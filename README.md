## Ansible 
####  - It is automation tool.
####  - It is used to deploy code on multiple servers

#### Installation on Ubuntu 18.04
```bash
785	 sudo apt update 
786	 mkdir Ansible
787	 cd Ansible/
788	 git init
789	 cd
790	 sudo apt install software-properties-common
791	 sudo apt-add-repository --yes --update ppa:ansible/ansible
792	 sudo apt install ansible
```
#### host file where all target ip to be kept
```bash
509	 cd /etc/ansible/
510	 ld
511	 ls
512	 cp hosts hosts.bkp
513	 >hosts
514	 vim hosts
```
