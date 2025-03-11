# example-traefik

```
├── README.md
├── apps
│   └── api
│       ├── Dockerfile
│       ├── go.mod
│       ├── go.sum
│       └── main.go
├── docker-compose.yaml
├── dozzle
│   └── data
│       └── users.yml
├── grafana
│   └── provisioning
│       ├── dashboards
│       │   └── dashboard.yaml
│       └── datasources
│           └── datasource.yaml
├── loki
│   └── config.yaml
└── promtail
    └── config.yaml```

```shell
docker compose up -d
```

```shell
# generate dozzle users
docker run amir20/dozzle generate admin --password secret --email adiatma.mail@gmail.com --name "Adiatma Kamarudin" > dozzle/data/users.yml
```
