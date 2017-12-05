# Hadoop 'cluster' in a Docker container

## Summary
The image contains
- Yarn
- Spark
- Kudu
- Impala
- Sqoop
- HDFS

## Running the container

```bash
$ docker-compose build
$ docker-compose up

```

Hadoop services are started separately from the container

```bash
$ docker-compose exec hadoop /run-all-services.sh
```
