# Fleek Node

## Docs
[https://github.com/fleek-network/ursa/tree/main/docker/full-node](https://github.com/fleek-network/ursa/tree/main/docker/full-node)

## Build
    docker-compose build
## Init
    EMAIL="mp@gmail.com" DOMAINS="monpham.org" bash init-letsencrypt.sh
## Run
    docker-compose up -d
## Backup
    cat /root/.ursa/keystore/default.pem