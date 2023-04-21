# Strapi 4 Todo application with Postgresql

## Setup on Local

```shell
docker volume create strapi-store

docker run --name postgresql-strapi-4 -e POSTGRES_PASSWORD=mysecretPassw0rd -e PGDATA=/var/lib/postgresql/data/pgdata -v strapi-store:/var/lib/postgresql/data -d -p 5432:5432 postgres
```
