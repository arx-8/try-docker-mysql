## How to run

```s
# Up
cd dockerfiles/
docker-compose up -d

# Check
docker ps

# Login from container
docker exec -it my-db /bin/bash
mysql -uroot -ptoor

# (or Login from host)
mysql -uroot -ptoor -h 127.0.0.1 -P 3306

# Exec SQL
show databases;
show create database my_db_db;
select * from my_db_db.movies;

# Down
docker-compose down
```
