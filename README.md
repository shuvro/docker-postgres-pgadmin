# Postgresql & PgAdmin powered by docker-compose


## Requirements:
* docker >= 17.12.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd docker-postgres-pgadmin`
* Run this command `docker-compose up -d`


## Environments
This Compose file contains the following environment variables:

* `POSTGRES_USER` the default value is **postgres**
* `POSTGRES_PASSWORD` the default value is **123456**
* `PGADMIN_PORT` the default value is **5050**
* `PGADMIN_DEFAULT_EMAIL` the default value is **lord@shuvro.me**
* `PGADMIN_DEFAULT_PASSWORD` the default value is **admin**

## Access to postgres: 
* `localhost:5432`
* **Username:** postgres (as a default)
* **Password:** 123456 (as a default)

## Access to PgAdmin: 
* **URL:** `http://localhost:5050`
* **Username:** lord@shuvro.me (as a default)
* **Password:** admin (as a default)

## Add a new server in PgAdmin:
* **Host name/address** `postgres`
* **Port** `5432`
* **Username** as `POSTGRES_USER`, by default: `postgres`
* **Password** as `POSTGRES_PASSWORD`, by default `123456`