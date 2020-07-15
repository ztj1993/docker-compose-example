# Docker 应用示例
```
git clone https://github.com/ztj1993/docker-example.git
```

### mysql
MySQL
````
cd mysql

export MYSQL_HOSTNAME=mysql
export MYSQL_CONTAINER_NAME=mysql
export MYSQL_ROOT_PASSWORD=123456

docker-compose -p core up -d mysql
````

### mysql-user-db
MySQL User Password Database
```
cd mysql-user-db

export MYSQL_HOST=mysql
export MYSQL_USER=root
export MYSQL_PASSWORD=${MYSQL_ROOT_PASSWORD:-123456}

export NEW_DB_USER=new_user
export NEW_DB_PASSWORD=123456
export NEW_DB_NAME=new_user_test

docker-compose up
docker-compose down
```
