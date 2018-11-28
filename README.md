> author: Michał Powała <br>
> source repository: [docker-postgresql](https://github.com/Crix4lis/docker-postgresql)

# docker-postgresql
This repository is basicly ready to use database docker image based on [official postresql docker image](https://hub.docker.com/_/postgres/)

# HOW TO RUN AND CONFIGURE
1. Install Docker: [OFFICIAL INSTRUCTION](https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-using-the-repository)
1. Install Compose: [OFFICIAL INSTRUCTION](https://docs.docker.com/compose/install/#install-compose)
1. Change directory to dir you cloned the repo and type: `docker-compose up -d`
1. Open your database client and configure with:
    - database user: `dbuser`
    - database name: `app-db`
    - database password: `abcdef`
> You can use web client by typing in address field: `localhost:8080` and provide data from (4)