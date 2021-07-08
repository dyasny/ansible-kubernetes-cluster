# Bootstrapping a kubernetes cluster using ansible
 
 Creating a kubernetes cluster via ansible.
 
# Prerequisites:
* You should configure passwordless root for your ansible user
* You should configure ssh access with ansible user's ssh key.
* You should have an inventory file in place. 

After cloning this repo you can bootstrap your cluster with
```
ansible-playbook install-kubernetes.yml -v
```
Currently tested on Ubuntu 20
