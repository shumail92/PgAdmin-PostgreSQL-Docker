# PgAdmin-PostgreSQL-Docker

### User docker-compose to run PgAdmin & PostgreSQL in Docker containers
 
This docker-compose file will initiate 2 docker containers. One with PostgreSQL & other with PgAdmin. Before running it, change volumes according to your filesystem respectively otherwise it will not work.

To start these containers, first make sure that docker is running and then execute `docker-compose up` in root of this repo.

The default username & password of PgAdmin is 
```
email: pgadmin4@pgadmin.org
password: admin
```

Note: When you add new server in PgAdmin, make sure you enter 'postgres' in hostname. Because of docker network, it will itself connect to the postgres instance running in its separate container.

Enjoy! 
