# Compose file for CockroachDB

## Start CockroachDB

```
docker compose up -d
```

## Connection string

```
postgres://cockroach:1234@localhost:26257/<database>
```

## SQL Console

```
docker compose exec -it cockroachdb cockroach sql --insecure
```

## Web Console

https://localhost:8080/
