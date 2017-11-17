# guacamole-docker-compose

```bash
git clone https://github.com/DmitryZagr/guacamole-docker-compose.git
cd guacamole-docker-compose/init
docker run --rm guacamole/guacamole /opt/guacamole/bin/initdb.sh --postgres > initdb.sql
cd ..
docker-compose up -d
```

Then go to `http://DOCKER_HOST:8080/guacamole/`

Log in as user: `guacadmin` and password: `guacadmin`.
