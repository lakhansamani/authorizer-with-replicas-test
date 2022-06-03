# Authorizer with replica test

It should sync env cache via redis instead of in-memory

## How to start

```sh
docker-compose -f docker-compose.yaml up --scale authorizer=2
```
