# Distributed DataBase (a.k.a) ddb

## Current Status

* nothing
* making use cases,objectives.and requirements.

## Objectives

### OS,Platforms

* run on linux
* run on clouds

### Key Value Store

* with global lock, region lock, node lock

### Sorted List Store

### Last Write Wins

* ddb:set({B,K},V).
* ddb:get({B,K}).
* ddb:get_in({B,KList}).
* ddb:list_all(B). 
* ddb:for_each(B,Fun).

* ddb:set_values({B,K},Props).
* ddb:get_values({B,K},Fields).
* ddb:get_in({B,KList},Fields).
* ddb:list_all(B,Fields). 
* ddb:for_each(B,Fun).

* ddb:add_to_set({B,K},V)
* ddb:add_to_set({B,K},V,FunOrderBy)
* ddb:get_set({B,K})
* ddb:get_set({B,K},FunOrderBy).
 
* ddb:add_to_list({B,K},V)
* ddb:add_to_list({B,K},V,FunOrderBy)
* ddb:get_list({B,K})
* ddb:get_list({B,K},FunOrderBy).

* ddb:add_to_map({B,K},V)
* ddb:get_map({B,K})

### Atomic Operations

* ddb:atomic_set({B,K},V,Actor).
* ddb:atomic_set_if({B,K},V,If,Actor).
* ddb:atomic_set_if_get({B,K},V,If,Actor).
* ddb:atomic_set_get({B,K},V,Actor).
* ddb:atomic_get({B,K}).

* ddb:atomic_add_to_set({B,K},V,Actor)
* ddb:atomic_add_to_set({B,K},V,FunOrderBy,Actor)
* ddb:atomic_get_set({B,K})
* ddb:atomic_get_set({B,K},FunOrderBy).

* ddb:add_count({B,K},V,Actor).
* ddb:add_count_get({B,K},V,Actor).
* ddb:get_count({B,K}).
* ddb:get_counts_in({B,KList}.

### Transactional Batch Writing Operations

* ddb:begin_transaction(TR,Actor).
* ddb:add_to_transaction(TR,Op).
* ddb:end_tranction(TR,Actor).


### support subset of SQL

### No Single of Failure , Multi Master
* write to any node, read from any node

### Multi Datacenter Replication
* replication in a cluster
* replication between data centers

### Distributed Memory Cache
* in a node 
* in a cluster
* in multi datacenters

### Support Multiple Backends and Get Wisdom from
* rocksdb
* cassandra
* crate.io
* redis
* mySQL
* postgresQL
* influxDB
* riak
* mongoDB
* couchDB
* couchBase
* AWS S3
* Google Cloud Storage
* Google Cloud Datastore
* Google Big Query
* Google Big Table
* pinot
* rethinkDB
* realm
* cockrouch
* TiDB
* ssdb
* boltdb
* citusDB
* druid.io
* 


### will be implemented in Erlang , rustlang, haskell, and c/c++

