# tp-dds-2022-entrega3
Ejemplo CRUD API JAVALIN para TP de dds 2022

Tiene solo la dependencia a Postgres, si van a usar otra db para pruebas locales, tienen
que agregar la misma al pom.xml

---
Ejemplo para levantar postgres con Docker (no hace falta, pueden descargar el instalador directamente)
```
docker run -d --name ddspostgres -p 5432:5432 -e POSTGRES_PASSWORD=mysecretpassword\
    -e PGDATA=/var/lib/postgresql/data/pgdata -v ${PWD}/posgresdb:/var/lib/postgresql/data postgres:14

```
