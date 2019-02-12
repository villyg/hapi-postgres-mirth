# mirth-connect-docker

Mirth-Connect Docker Stack (Mirth-Connect container + Mysql container + PHPMyAdmin container)

## Prerequirements

- Docker
- Java

## Build HAPI

> in hapi folder - mvn package

## Build Mirth-Connect docker image

  > \> docker-compose build

## Start
> \> docker-compose up

## Stop Mirth-Connect-Docker stack

  > \> docker-compose down

## Connect to PHPMyAdmin

- url: [http://localhost:8181]()
- user: *root*
- password: *password*

## Connect to MySQL

Use your preferred MySQL client connected to *localhost* port *3306*
(admin user: *root* / password: *password*)

### Mirth database

- database: *mirth-test*
- user: *mirth*
- password: *password*

## Connect to Mirth-Connect

Double-click on *./webstart.jnlp* to start the Mirth-Connect client
(user: *admin* / password: *admin* )

or

browse to [http://localhost:8083]() to access web client.

## Connect to PostgreSQL
- port: 5432
- database: hapi
- user: dbadmin
- password: MyCrazyDbPassw0rd!!!
