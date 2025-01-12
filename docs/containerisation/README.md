# Keycloak Containerisation 

This page contains the documentation around how to deploy the keycloak in a container environment.

## Quick Start

Keycloak can be deployed in any OCI(Open Container Initiative) Compatible container runtimes like Docker and Podman

We are primarily looking at

 - Podman in our implementations as it is best for local/home deployments to run as non-root user.

The below quick commands will bring up a container up in each environment.

### Podman Container

```bash
podman run -p 127.0.0.1:8080:8080 -e KC_BOOTSTRAP_ADMIN_USERNAME=admin -e KC_BOOTSTRAP_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:26.0.7 start-dev
```

### Docker Container

```bash
docker run -p 127.0.0.1:8080:8080 -e KC_BOOTSTRAP_ADMIN_USERNAME=admin -e KC_BOOTSTRAP_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:26.0.7 start-dev
```


## References

| Name                   | Reference Link |
| ---------------------- | -------------- |
| Podman Container Guide |   [Link](https://www.keycloak.org/getting-started/getting-started-podman)             |
| Docker Container Guide |      [Link](https://www.keycloak.org/getting-started/getting-started-docker)          |
