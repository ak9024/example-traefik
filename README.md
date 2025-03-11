# example-traefik

```shell
docker compose up -d
```

```shell
# generate dozzle users
docker run amir20/dozzle generate admin --password secret --email adiatma.mail@gmail.com --name "Adiatma Kamarudin" > dozzle/data/users.yml
```

### Services

- traefik as a loadbalancer
- nginx
- dozzle for container logs
- api (go apps)
