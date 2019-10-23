---
title: ElasticSearch Docker
comments: true
tags:
  - ElasticSearch
categories:
  - - ElasticSearch
    - Install
keywords:
  - ElasticSearch
date: 2019-10-23 16:22:31
updated: 2019-10-23 16:22:31
---
# ElasticSearch Docker

## Reference

https://hub.docker.com/_/elasticsearch

## Docker Pull

```bash
docker pull elasticsearch:7.4.0
```

## Docker Network

```bash
docker network create elasticsearch-network
```

## Docker Run

```bash
docker run -d --name elasticsearch --net elasticsearch-network -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" elasticsearch:7.4.0
```

## Test ElasticSearch

```bash
curl -X GET 127.0.0.1:9200 | pbcopy
```

```json
{
  "name" : "da513fa5d3cb",
  "cluster_name" : "docker-cluster",
  "cluster_uuid" : "Mad8RO6BQmm7bmlbF-jtxQ",
  "version" : {
    "number" : "7.4.0",
    "build_flavor" : "default",
    "build_type" : "docker",
    "build_hash" : "22e1767283e61a198cb4db791ea66e3f11ab9910",
    "build_date" : "2019-09-27T08:36:48.569419Z",
    "build_snapshot" : false,
    "lucene_version" : "8.2.0",
    "minimum_wire_compatibility_version" : "6.8.0",
    "minimum_index_compatibility_version" : "6.0.0-beta1"
  },
  "tagline" : "You Know, for Search"
}
```