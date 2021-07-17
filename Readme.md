# Graphpl Beispiel 
Beispiel mit juniper und diesel nach [Tutorial](https://dev.to/open-graphql/building-powerful-graphql-servers-with-rust-3gla)

## Voraussetzung
* Postgres DB 

## Start
* Startt Postgres DB Docker mit `cd docker/postgres` und `docker-compose up`
* Migrage datane aus ordner migrations up.sql mit `diesel migration run`
* Start Rest und Graphql `cargo run`

## Postgres
* Login `psql -h localhost -p 5432 -U docker db`
* List tables `\dt`
* Conntect to Database `\c other_than_db`
