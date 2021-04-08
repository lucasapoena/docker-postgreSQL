![PostgreSQL](https://wiki.postgresql.org/images/9/9a/PostgreSQL_logo.3colors.540x557.png)

# Docker - PostgreSQL

### PostgreSQL + pgAdmin 4

### Requirements

**MacOS:**

Install [Docker](https://docs.docker.com/docker-for-mac/install/) and [Docker-compose](https://docs.docker.com/compose/install/#install-compose)

**Windows:**

Install [Docker](https://docs.docker.com/docker-for-windows/install/) and [Docker-compose](https://docs.docker.com/compose/install/#install-compose)

**Linux:**

Install [Docker](https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/) and [Docker-compose](https://docs.docker.com/compose/install/#install-compose).

### How to use

Clone the project to your local repository:

```
git clone https://github.com/lucasapoena/docker-postgreSQL
```

Initialize your containers:

```
cd docker-postgreSQL
./start
```

### Panels

Enjoy your new panels!

**PgAdmin4:** http://localhost:8080

### Images used
[postgres:latest](https://hub.docker.com/layers/postgres/library/postgres/latest/images/sha256-5dab16d1b9c77b57d5a2300d43eda2e23cc7a9ea84505b5eef3e59b500c4b555?context=explore)

[dpage/pgadmin4:latest](https://hub.docker.com/r/dpage/pgadmin4/)

### Features commands

| Commands  | Description  | Options & Examples |
|---|---|---|
| `./start`  | Initializes its containers  | |
| `./stop`  | Stop your project containers  | |
| `./kill`  | Stops containers and removes containers, networks, volumes, and images created to the specific project  | |

### References
[Pg4Admin](https://www.pgadmin.org/docs/pgadmin4/latest/container_deployment.html)

### License

MIT © 2019 [Lucas Apoena](https://github.com/lucasapoena/) and [contributors](https://github.com/lucasapoena/zabbix-server-docker/graphs/contributors).
