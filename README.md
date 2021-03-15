# ansible_by_roles
Deployment Wordpress for Ubuntu 20.04

Deploymant tree

├── ansible.cfg
├── hosts
├── README.md
├── roles
│   ├── mariadb
│   │   ├── defaults
│   │   │   └── main.yml
│   │   ├── README.md
│   │   └── tasks
│   │       ├── db.yml
│   │       ├── main.yml
│   │       ├── mariadb.yml
│   │       └── pymysql.yml
│   ├── nginx
│   │   ├── defaults
│   │   │   └── main.yml
│   │   ├── handlers
│   │   │   └── main.yml
│   │   ├── README.md
│   │   ├── tasks
│   │   │   └── main.yml
│   │   └── templates
│   │       └── nginx_config
│   └── wordpress
│       ├── README.md
│       └── tasks
│           └── main.yml
└── WP_install.yml

