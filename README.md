# Distributed DataBase (a.k.a) ddb

## Current Status

* nothing
* making use cases,objectives.and requirements.

## Objectives

### No Single of Failure , Multi Master
* write to any node, read from any node

### Multi Datacenter Replication
* replication in a cluster
* replication between data-centers

### AUTO SCALING
* running DB with auto scaling is not common. However, it is valuable if achieved.

### 

### OS,Platforms

* run on linux(CoreOS or Debian)
* run on GCE( my favorite cloud system)

### Key Value Store
### Eventually Consistency 
### Strong Consistency
### Sorted List Store
### Subset of SQL

### Distributed Memory Cache
* in a node 
* in a cluster
* in multi datacenters
* 

### will be implemented in Erlang , rust, haskell, julia, go, and c/c++

### Protocols to communicate with clients

* HTTP(S)/1.x, HTTP(S)/2
* TCP
* SCTP 

### Clients to be supported primarily

* Erlang
* Go
* Node.js
* PHP


### Support Multiple Backends and Get Wisdom from
* cassandra
* rocksdb
* cockrouch
* citusDB
* crate.io
* druid.io
* redis
* mySQL
* postgresQL
* influxDB
* riak
* mongoDB
* couchDB
* couchBase
* pinot
* rethinkDB
* realm
* TiDB
* ssdb
* boltdb
* scalaris
* AWS S3
* Google Cloud Storage
* Google Cloud Datastore
* Google Big Query
* Google Big Table
