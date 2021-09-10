# Assignment 1

![](https://docs.google.com/drawings/d/e/2PACX-1vTAjxZs49TvsxoPuoRhhS2SLuYIgsiDg90QcZqCJ3ZCw2u6WHlFoRqAdvjVmWtgfj_C3sw2DqsYLkez/pub?w=960&h=720)

You will be building a data replicator from Postgres to MongoDB. You must use GRPC with [gprc requests](https://github.com/spaceone-dev/grpc_requests) wrapper as a communication protocol. It is an one-way replication and expects to be near realtime aside from the GRPC latency.

- Postgres version 13.4
- MongoDB version 5.0.2

You will be using [wal2json](https://access.crunchydata.com/documentation/wal2json/2.0/) plugin to decode binary WAL to JSON format.

## Test Data

### Postgres schema
* DB name: college
* Table: students, classes

## File naming

* client_repl.py
* server_repl.py
