# Nginx with ModSecurity

## Acknowledgement

This repository is fork from [xJonathanLEI/nginx-modsecurity-docker](https://github.com/xJonathanLEI/nginx-modsecurity-docker).

## Docker Hub

Built images are available on [Docker Hub](https://hub.docker.com/r/xjonathanlei/nginx-modsecurity).

## Configuration

The following environment variables are available for simple configuration. For more sophisticated scenarios you need to edit conf files directly.

### MODSECURITY_DETECTION_ONLY

Whether ModSecurity rule engine should be running in `DetectionOnly` mode. Can be one of the following:

- true
- false

Defaults to `false`.
