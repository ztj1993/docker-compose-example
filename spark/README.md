# Spark Test

### Run
```
docker-compose up
docker-compose down

docker exec -it spark-submit /bin/sh
mkdir -p /srv/spark-script/testing/src
cd /srv/spark-script/testing
python3 -m venv --system-site-packages .
source /srv/spark-script/testing/bin/activate
cd /srv/spark-script/testing/src
deactivate
```

### Reference
- https://github.com/big-data-europe/docker-spark
