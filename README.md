# docker-komodo
Komodo docker management install.


## usage
Clone this repository to your local machine, edit the config file to match your environment, and run docker compose.

```bash
git clone https://github.com/kris-smarthome/docker-komodo.git
cd docker-komodo
nano .env
docker compose up -d
```

> [!NOTE]
> This stack incldes traefik, create the traefik network before deploying this stack: `docker network create -d bridge traefik`