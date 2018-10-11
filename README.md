## Usage

### Clone repository
```shell
git clone git@github.com:siddou/guacamole-mysql.git
cd guacamole-mysql
```
### Get initdb:
```shell
docker run --rm guacamole/guacamole /opt/guacamole/bin/initdb.sh --mysql > sql-scripts/initdb.sql
```
### Run:
```shell
docker-compose up -d
```





