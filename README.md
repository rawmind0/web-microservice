web-microservices
============

This repo geenrates docker-compose and rancher-compose files on pipeline.

## Default values

```
DOCKER_COMPOSE=${DOCKER_COMPOSE:-"docker-compose.yml"}
RANCHER_COMPOSE=${RANCHER_COMPOSE:-"rancher-compose.yml"}
DOCKER_SHIPPING=${DOCKER_SHIPPING:-"rawmind/web-shipping:0.1-0"}
DOCKER_PAYMENTS=${DOCKER_PAYMENTS:-"rawmind/web-payments:0.1-3"}
DOCKER_INVENTORY=${DOCKER_INVENTORY:-"rawmind/web-inventory:0.1-0"}
DOCKER_GATEWAY=${DOCKER_GATEWAY:-"rawmind/web-gateway:0.1-3"}
RANCHER_LB=${RANCHER_LB:-"rancher/lb-service-haproxy:v0.7.9"}
PUBLISH_PORT=${PUBLISH_PORT:-8080}
```

Values could be overwrite before generate files.

## Example

./docker-compose.yml.tmpl
./rancher-compose.yml.tmpl
