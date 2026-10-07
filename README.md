# Awesome-Managed-Nosql-Key-Value-Database

## Top Managed NoSQL Key-Value Database Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Managed Key-Value Stores, Document Databases & Self-Hosted NoSQL*  

**Last updated: October 2026**



This repository tracks notable **commercial managed NoSQL databases** and **open-source projects** that store and retrieve data as key-value pairs, documents, or wide-column structures — powering high-scale applications, caching, session stores, and real-time workloads without operational overhead.



**Examples** include Amazon DynamoDB, Google Cloud Bigtable, Azure Cosmos DB, ScyllaDB Cloud, DataStax Astra DB, Aerospike Cloud, Couchbase Capella, Redis Enterprise Cloud, Upstash, and Fauna (the category leaders).



**Open-source emphasis**: Managed NoSQL key-value databases are anchored by **Apache Cassandra** and **ScyllaDB** for wide-column storage, **Redis** and **Valkey** for in-memory key-value, **MongoDB** and **CouchDB** for document stores, and **Aerospike** for high-performance caching. **TiKV**, **FoundationDB**, and **etcd** provide distributed key-value foundations. **Dragonfly** and **KeyDB** offer high-performance Redis alternatives. **RocksDB** and **LevelDB** power embedded key-value engines. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon DynamoDB](https://aws.amazon.com/dynamodb/)**

  **AWS's fully managed key-value and document database** — single-digit millisecond latency at any scale . **DynamoDB Accelerator (DAX)** for microsecond read performance . **Global tables for multi-region active-active replication** . **The reference for serverless key-value databases** . **Best for AWS-native applications** .



- **[Google Cloud Bigtable](https://cloud.google.com/bigtable)**

  **Google's fully managed wide-column NoSQL database** — petabyte-scale with HBase API compatibility . **Powers Google Search, Analytics, and Maps** . **Best for large-scale analytical workloads** .



- **[Azure Cosmos DB](https://azure.microsoft.com/en-us/products/cosmos-db/)**

  **Microsoft's globally distributed multi-model database** — key-value, document, graph, and column-family APIs . **Turnkey global distribution with multi-region writes** . **Best for globally distributed applications** .



- **[ScyllaDB Cloud](https://www.scylladb.com/)**

  **Managed ScyllaDB** — Cassandra-compatible with 10x performance . **Shard-per-core architecture with auto-scaling** . **Best for high-throughput workloads** .



- **[DataStax Astra DB](https://www.datastax.com/products/datastax-astra)**

  **Managed Apache Cassandra** — serverless with vector search capabilities . **Best for Cassandra workloads without operations** .



- **[Aerospike Cloud](https://aerospike.com/)**

  **Managed Aerospike** — sub-millisecond latency at scale . **Best for real-time bidding and fraud detection** .



- **[Couchbase Capella](https://www.couchbase.com/products/capella/)**

  **Managed Couchbase** — document database with SQL-like query language . **Best for mobile and edge applications** .



- **[Redis Enterprise Cloud](https://redis.com/cloud/)**

  **Managed Redis with enterprise features** — active-active geo-distribution and modules . **Best for caching and real-time applications** .



- **[Upstash](https://upstash.com/)**

  **Serverless Redis and Kafka** — pay-per-request pricing with global replication . **Best for serverless applications** .



- **[Fauna](https://fauna.com/)**

  **Serverless document database** — globally distributed with GraphQL API . **Best for serverless applications** .



## Open-Source GitHub Projects



### Wide-Column & Distributed Key-Value



- **[Apache Cassandra](https://github.com/apache/cassandra)**

  **The leading open-source distributed wide-column database**, Apache-2.0 licensed with **9,000+ GitHub stars** . **Linear scalability with no single point of failure** . **Multi-datacenter replication with tunable consistency** . **The foundation for DataStax Astra** . **Best for high-scale distributed workloads** .



- **[ScyllaDB](https://github.com/scylladb/scylladb)**

  **Cassandra-compatible database written in C++**, AGPL-3.0 licensed with **3,000+ GitHub stars** . **Shard-per-core architecture** — 10x throughput with lower latency . **No JVM, no GC pauses** . **Best for high-performance Cassandra workloads** .



- **[TiKV](https://github.com/tikv/tikv)**

  **Distributed transactional key-value database**, Apache-2.0 licensed with **16,000+ GitHub stars** . **Raft-based consensus with ACID transactions** . **The storage layer for TiDB** . **Best for distributed OLTP** .



- **[FoundationDB](https://github.com/apple/foundationdb)**

  **Distributed key-value store from Apple**, Apache-2.0 licensed with **15,000+ GitHub stars** . **ACID transactions with multi-key atomicity** . **Layered architecture for multiple data models** . **Best for building distributed databases** .



- **[etcd](https://github.com/etcd-io/etcd)**

  **Distributed reliable key-value store**, Apache-2.0 licensed with **50,000+ GitHub stars** . **Raft consensus with watch support** . **The foundation for Kubernetes** . **Best for configuration and service discovery** .



### In-Memory Key-Value Stores



- **[Redis](https://github.com/redis/redis)**

  **The most widely deployed in-memory key-value store**, RSALv2/SSPL licensed with **70,000+ GitHub stars** . **Sub-millisecond latency with rich data structures** . **Pub/sub, streams, and Lua scripting** . **Best for caching and real-time applications** .



- **[Valkey](https://github.com/valkey-io/valkey)**

  **The Linux Foundation fork of Redis**, BSD-3-Clause licensed with **15,000+ GitHub stars** . **Redis-compatible with open governance** . **Best for Redis without licensing concerns** .



- **[Dragonfly](https://github.com/dragonflydb/dragonfly)**

  **Modern Redis-compatible in-memory store**, BSL licensed with **25,000+ GitHub stars** . **Multi-threaded architecture** — 25x throughput over Redis . **Best for high-performance caching** .



- **[KeyDB](https://github.com/Snapchat/KeyDB)**

  **Multi-threaded Redis fork from Snapchat**, BSD-3-Clause licensed . **Active replication and sub-millisecond latency** . **Best for high-throughput Redis workloads** .



- **[Memcached](https://github.com/memcached/memcached)**

  **The classic distributed memory object caching system**, BSD-3-Clause licensed with **13,000+ GitHub stars** . **Simple and fast key-value caching** . **Best for simple caching** .



### Document Databases



- **[MongoDB](https://github.com/mongodb/mongo)**

  **The leading open-source document database**, SSPL licensed with **27,000+ GitHub stars** . **Flexible schema with rich query language** . **Replica sets and sharding for scale** . **Best for document-oriented applications** .



- **[CouchDB](https://github.com/apache/couchdb)**

  **Document database with HTTP API**, Apache-2.0 licensed with **6,000+ GitHub stars** . **Multi-master replication with conflict resolution** . **Best for offline-first applications** .



- **[FerretDB](https://github.com/FerretDB/FerretDB)**

  **MongoDB-compatible database on PostgreSQL**, Apache-2.0 licensed . **Drop-in MongoDB replacement** . **Best for MongoDB without SSPL** .



- **[RethinkDB](https://github.com/rethinkdb/rethinkdb)**

  **Real-time document database**, Apache-2.0 licensed . **Changefeeds for real-time updates** . **Best for real-time applications** .



### Embedded Key-Value Stores



- **[RocksDB](https://github.com/facebook/rocksdb)**

  **Embedded key-value store from Facebook**, Apache-2.0/GPL licensed with **30,000+ GitHub stars** . **High-performance persistent storage** . **The foundation for many databases** . **Best for embedded storage** .



- **[LevelDB](https://github.com/google/leveldb)**

  **Fast key-value storage library from Google**, BSD-3-Clause licensed with **36,000+ GitHub stars** . **Embedded persistent key-value store** . **Best for embedded storage** .



- **[BadgerDB](https://github.com/dgraph-io/badger)**

  **Embedded key-value store in Go**, Apache-2.0 licensed with **14,000+ GitHub stars** . **LSM tree with SSDs optimized** . **Best for Go applications** .



- **[LMDB](https://github.com/LMDB/lmdb)**

  **Lightning memory-mapped database**, OpenLDAP Public License . **Ultra-fast embedded key-value store** . **Best for high-performance embedded storage** .



### Additional Strong Open-Source Options



- **Riak KV** — Distributed key-value store with CRDTs .

- **Aerospike** — High-performance NoSQL database (open-source community edition) .

- **Couchbase** — Document database (open-source community edition) .

- **ArangoDB** — Multi-model database with key-value, document, and graph .

- **OrientDB** — Multi-model database with key-value support .

- **RavenDB** — Document database with ACID transactions .

- **CockroachDB** — Distributed SQL (not pure NoSQL but includes key-value layer) .

- **YugabyteDB** — Distributed SQL with key-value storage layer .

- **Consul KV** — Key-value store within Consul .



**Frameworks for building custom managed NoSQL key-value solutions**: Combine **Apache Cassandra** or **ScyllaDB** for distributed wide-column storage . Use **Redis** or **Valkey** for in-memory key-value caching . Deploy **TiKV** for distributed transactional key-value with ACID . Choose **MongoDB** or **CouchDB** for document storage . Integrate **FoundationDB** for building custom distributed databases . Use **RocksDB** or **BadgerDB** for embedded key-value storage . Note that true managed NoSQL with global infrastructure, automatic scaling, and vendor-supported SLAs (DynamoDB, Cosmos DB, ScyllaDB Cloud) remains primarily commercial territory; open-source stacks provide strong distributed storage, in-memory caching, and document database foundations that require integration for complete NoSQL deployments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- NoSQL key-value databases handle sensitive application data. Self-hosted solutions require proper security hardening, access controls, encryption at rest and in transit, and compliance with data privacy regulations.

- **License considerations**: Redis uses RSALv2/SSPL (not OSI), MongoDB uses SSPL, Dragonfly uses BSL, Cassandra uses Apache-2.0, and ScyllaDB uses AGPL-3.0. Verify licensing against your use case before committing .

- **Data modeling differs from relational** — NoSQL key-value stores require careful access pattern design. Poor key design leads to hot partitions and performance issues .

- **Consistency trade-offs** — Many NoSQL databases offer eventual consistency by default. Understand your consistency requirements before choosing .

- The open-source ecosystem provides strong distributed storage, in-memory caching, and document database foundations, but **global infrastructure, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for backend engineers, platform teams, and organizations seeking NoSQL database sovereignty.**

Let's make managed NoSQL key-value databases more open, transparent, and scalable.
