# Mesos Cluster Setup Using Ansible
It will install mesos cluster on 3 nodes for demo.

## Notes
```
It Doesn't support docker containers yet.
```

## Requirements
* vagrant

## TO RUN
* **STEP-1**
```
vagrant up
```

* **STEP-2**
```
vagrant ssh controller
```

* **STEP-3**
```
cd /home/vagrant/projects/playbooks
```

* **STEP-4**
```
ansible-playbook -i hosts/cluster-hosts.ini cluster-setup.yml
```
# Verification Links
* http://192.168.56.101:5050/#/
* http://192.168.56.101:8080/ui/#/apps

# Supported/Tested OS
* CentOS/7
