# MySQL User Password Database

### Environment
````
export MYSQL_HOST=mysql
export MYSQL_USER=root
export MYSQL_PASSWORD=${MYSQL_ROOT_PASSWORD:-123456}

export NEW_DB_USER=new_user
export NEW_DB_PASSWORD=123456
export NEW_DB_NAME=new_user_test
````

### Run
```
docker-compose up
docker-compose down
```

### Reference
- https://hub.docker.com/r/ztj1993/mysql-tools
- https://github.com/ztj1993/mysql-tools
