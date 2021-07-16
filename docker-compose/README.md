# lakeFS docker-compsoe

Compose file for lakeFS, with Hive and Trino


### Hive Client

Can access Hive Server using client, run under 'client' profile:

```sh
docker-compose --profile client run --rm hive-client
```

### Trino Client

Can access Trino using trino-cli, run under 'client' profile:

```sh
docker-compose --profile client run --rm trino-client
```
