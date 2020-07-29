FROM python:3.7.5-alpine3.10

LABEL maintainer="Ztj <ztj1993@gmail.com>"

# Spark
RUN apk add --no-cache bash openjdk8
RUN pip install --upgrade -i https://mirrors.aliyun.com/pypi/simple pip
RUN pip install --upgrade -i https://mirrors.aliyun.com/pypi/simple pyspark==2.4.5
