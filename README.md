# ansible_project

ansible-project/
│
├── ansible.cfg
├── inventory
├── playbook.yml
├── roles/
│   ├── ca_certificates/
│   │   ├── tasks/
│   │   │   └── main.yml
│   │   └── files/
│   │       ├── CA1.crt
│   │       ├── CA2.crt
│   │       └── CA3.crt
│   ├── application/
│   │   ├── tasks/
│   │   │   ├── main.yml
│   │   │   ├── deploy.yml
│   │   │   └── configure.yml
│   │   ├── templates/
│   │   │   ├── run.sh.j2
│   │   │   └── config.py.j2
│   │   └── files/
│   │       └── Example-1.1.2-py3-none-any.whl
│   └── security/
│       ├── tasks/
│       │   └── main.yml
│       └── files/
│           └── example.service
└── vars.yml

# Ansible_project
