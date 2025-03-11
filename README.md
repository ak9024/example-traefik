# example-traefik

```
.
├── ./apps/
│   └── ./apps/api
├── ./dozzle/
│   └── ./dozzle/data/
│       └── ./dozzle/data/users.yaml
└── ./docker-compose.yaml
```

```shell
docker compose up -d
```

```shell
# generate dozzle users
docker run amir20/dozzle generate admin --password secret --email adiatma.mail@gmail.com --name "Adiatma Kamarudin" > dozzle/data/users.yml
```
