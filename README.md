# streamaUsingDockerCompose
Streama using docker-compose &amp; nginx reverse proxy + letsencrypt


### Usage
Make sure that docker & docker-compose are installed.
1. git clone https://github.com/abdoofathy95/streamaUsingDockerCompose.git 
2. `$ docker network create nginx-proxy`
3. `$ docker-compose up -d`.
4. Make sure that the DNS reflected in the files point to the valid IP.
5. `$ docker-compose up -d`.
