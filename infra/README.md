# Sample infra

## Run infra

First set env var POSTGRES_PASSWORD as posrtgresql docker [docs require](https://hub.docker.com/_/postgres)

```bash
sh run_infra.sh
```

## Load data
```bash
sh load_data.sh
```

## Credentials
* **Mongodb**
    * Authentication: none
* **PostgreSQL**
    * User: postgres
    * Pass: postgress
