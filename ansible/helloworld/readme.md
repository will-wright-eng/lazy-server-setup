```bash
ansible-playbook -i inventory.yaml playbook.yaml
ansible webservers -m ping -i inventory.yaml
```

```
ansible-playbook -i inventory.yaml playbook.yaml

PLAY [My first play] *************************************************************************************************

TASK [Gathering Facts] ***********************************************************************************************
ok: [droplettwl]

TASK [Ping my hosts] *************************************************************************************************
ok: [droplettwl]

TASK [Print message] *************************************************************************************************
ok: [droplettwl] => {
    "msg": "Hello world"
}

PLAY RECAP ***********************************************************************************************************
droplettwl                 : ok=3    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
```

```
ansible webservers -m ping -i inventory.yaml
droplettwl | SUCCESS => {
    "ansible_facts": {
        "discovered_interpreter_python": "/usr/bin/python3"
    },
    "changed": false,
    "ping": "pong"
}
```
