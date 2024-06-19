# SQL-Mastery
Master SQL - Beginner to Expert


## Set-up
### 1. Create a docker volume:
   docker volume create --name postgres_volume_local -d local
### 2. Run (Go to the the directory where docker-compose.yml is present)
   docker compose up
### 3. Go to localhost:8080 to use pgAdmin 4, then provide following details to connect to the database from pgAdmin.
   pgAdmin Login: username - admin@admin.com, password-root
   Server Registration: Name - local_pg, Host: pgdb, port - 5432, maintenance database- my_db, username - root, password - root
