### Install mkcert

```shell
mkcert -install
```

### Generate certificates

```shell
cd certs

mkcert traefik.test *.traefik.test
```

### Run

```shell
export TRAEFIK_HUB_AGENT_TOKEN=token

docker-compose up -d
```
