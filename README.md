# caddy

```
cp .env.example .env
```

edit .env

```
docker network create reverse_proxy
docker volume create --name=caddy_data
```

```
docker-compose up -d
```

```
curl -H 'Host: whoami.localhost' http://127.0.0.1:80
```
