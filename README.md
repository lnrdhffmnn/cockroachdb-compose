# Compose file for CockroachDB

## Start CockroachDB

```
docker compose up -d
```

## Connection string

```
postgresql://root@localhost:26257/DATABASE?sslmode=disable
```

## SQL Console

```
docker compose exec -it cockroachdb cockroach sql --insecure
```

## Web Console

http://localhost:8080/
