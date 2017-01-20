# Provisioning Boilerplate

## Requirements

- Ansible

## The Directory Structure

```
.
├── README.md
├── common-roles
│   ├── base-amazonlinux
│   │   ├── tasks
│   │   │   └── main.yml
│   │   └── vars
│   │       └── main.yml
│   └── base-ubuntu
│       ├── tasks
│       │   └── main.yml
│       └── vars
│           └── main.yml
└── service-x
    ├── group_vars
    │   ├── all.yml
    │   ├── development.yml
    │   ├── production.yml
    │   └── testing.yml
    ├── hosts
    │   ├── development.ini
    │   ├── production.ini
    │   └── testing.ini
    ├── roles
    │   ├── application
    │   │   └── tasks
    │   │       └── main.yml
    │   ├── database
    │   │   └── tasks
    │   │       └── main.yml
    │   ├── middleware
    │   │   └── tasks
    │   │       └── main.yml
    │   └── packages
    │       └── tasks
    │           └── main.yml
    ├── site-development.yml
    ├── site-production.yml
    └── site-testing.yml
```

## Author

[ktrysmt](https://twitter.com/ktrysmt)

## License

MIT

