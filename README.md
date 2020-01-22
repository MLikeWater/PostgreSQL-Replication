# PostgreSQL-Replication

Three experiments with PostgreSQL database:
## 1. Flow replication
```
$ cd streaming_replication
$ docker-compose up # start container 
$ docker-compose down # stop and delete container
```

## 2. Logical replication

### 2.1 single Publisher and Subscriber
```
$ cd logical_replication
$ docker-compose up
$ docker-compose down
```

### 2.2 multiple Publishers
```
$ cd logical_replication_multi_master
$ docker-compose up
$ docker-compose down
```
