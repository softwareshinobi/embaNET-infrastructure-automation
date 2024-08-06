# EmbaNET Infrastructure Automation w/ Ansible

Provision scripts, playbooks, just all the stuff for managing embaNET using ansible.

## How to use

## install anbible on ubuntu

sudo apt update
sudo apt install ansible
sudo apt install sshpass

## run the ping cd

```
cd playbooks/ping/
```
```
bash embaNET-ping-all.bash
```

## should look like this:

```
revuelto.embanet.softwareshinobi.digital | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3"
    },
    "changed": false,
    "ping": "pong"
}
countach.embanet.softwareshinobi.digital | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3"
    },
    "changed": false,
    "ping": "pong"
}
huracan.embanet.softwareshinobi.digital | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3"
    },
    "changed": false,
    "ping": "pong"
}
```
