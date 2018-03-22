# Docker-database
> starts its own database in the serer that other containers can connect to

## Requirements

### Server

* [Docker](http://docs.docker.com/linux/started/)
* [Docker Compose](https://docs.docker.com/compose/install/)

### How to use
Place the schema file eg `schema.sql` in the `db_dump` folder
and issue the command below.

```bash
git clone https://github.com/mistaguy/docker-database.git
cd docker-database
cp .env.example .env
chmod 600 .env
# > Edit configuration in .env

docker-compose up -d

```

## License

This software is licensed under the [MIT license](https://github.com/mistaguy/docker-database/blob/master/LICENSE).

© 2018 Mistaguy