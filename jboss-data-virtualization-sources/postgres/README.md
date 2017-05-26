
## Postgres Docker Container

```sh
docker run -d --name postgres -e POSTGRES_USER=dvadmin -e POSTGRES_PASSWORD=dvadmin -p 5432:5432 vchintal/postgres
```

## Postgres JDBC Connection

```
Username: dvuser
Password: dvuser
JDBC URL: jdbc:postgresql://localhost:5432/eucustomers
```
