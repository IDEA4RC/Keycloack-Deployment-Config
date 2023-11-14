# Keycloak install 

1. Using docker

Change the default admin password for better security.

- To run the keycloak compose run:

```shell
docker compose up -d 
```

2. You can import the [IDEA4RC](./realm-export.json) realm and it's clients on keycloak to replicate the enviroment for the [IDEA4RC infrastructure workshop](https://gitlab.lst.tfo.upm.es/idea4rc/workshop-infrastructure) 