web-microservice
================

This repo geenrates docker-compose and rancher-compose files on pipeline.

## Default values

```
DOCKER_SHIPPING=${DOCKER_SHIPPING:-"rawmind/web-shipping:0.1-0"}
DOCKER_PAYMENTS=${DOCKER_PAYMENTS:-"rawmind/web-payments:0.1-3"}
DOCKER_INVENTORY=${DOCKER_INVENTORY:-"rawmind/web-inventory:0.1-0"}
DOCKER_GATEWAY=${DOCKER_GATEWAY:-"rawmind/web-gateway:0.2-0"}
```

Values could be overwrite before generate files.

```
./manifests.yml.tmpl
```
