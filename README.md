# pondus-duo

## How to run:
```
docker-compose run --rm k6 run ./script.js
```

```
docker-compose run --rm k6 run --vus 10 --duration 30s  ./script.js
```

```
docker-compose run --rm k6 run --insecure-skip-tls-verify ./script.js
```
