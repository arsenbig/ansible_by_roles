
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

11 directories, 17 files

![Screenshot_1](https://user-images.githubusercontent.com/79520412/111215954-3782e280-85ed-11eb-81c3-d6df10e98b77.png)
