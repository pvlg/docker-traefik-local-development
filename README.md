### Install mkcert

```shell
mkcert -install
```

### Generate certificates

```shell
cd certs

mkcert traefik.test
mkcert *.docker.test
```

### Run

```shell
cp docker-compose.override.dist.yml docker-compose.override.yml

docker-compose up -d
```
