# Rust Axum Backend

## PostgreSQL
```
docker run --name pgdev -e POSTGRES_PASSWORD= -e POSTGRES_DB=axum_backend -p 5432:5432 -d postgres
```
```
sqlx database create
sqlx migrate add -r users

```