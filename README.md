# Master Relational Database and SQL
RDBMS and SQL - Beginner to Expert


## 1. Set-up
### a. Create a docker volume:
   docker volume create --name postgres_volume_local -d local
### b. Run (Go to the the directory where docker-compose.yml is present)
   docker compose up
### c. Go to localhost:8080 to use pgAdmin 4, then provide following details to connect to the database from pgAdmin.
   pgAdmin Login: username - admin@admin.com, password-root
   
   Server Registration: Name - local_pg, Host: pgdb, port - 5432, maintenance database- my_db, username - root, password - root
