# Ansible-roles

mkdir ueransim

ansible-galaxy init ueransim


├── defaults
│   └── main.yml
├── files
├── handlers
│   └── main.yml
├── meta
│   └── main.yml
├── README.md
├── tasks
│   └── main.yml
├── templates
├── tests
│   ├── inventory
│   └── test.yml
└── vars
    └── main.yml


touch runsetup.yml - outside ueransim folder

 - hosts: demo
   become: yes
   roles:
   - ueransim



vim main.yml - inside task folder 

- import_tasks: install-depd.yaml



