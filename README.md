# distributed datastores

| Name          | SQL | Doc | Mem | C.Rd | TS |
| ------------- | --- | --- | --- | ---- |--- |
| MySQL         |  Y  |     |     |   Y  |    |
| MySQL/TokuDB  |  Y  |     |     |   Y  |    |
| PostgreSQL    |  Y  |  /  |     |   Y  |    |
| CitusData     |  Y  |     |     |      |    |
| Aurora        |  Y  |     |     |   Y  |    |
| CockroachDB   | sQL |     |     |   Y  |    |
| MongoDB       |     |  Y  |     |      |    |
| MongoDB/TokuMX|     |  Y  |     |      |    |
| RethinkDB     |     |  Y  |     |      |    |
| CouchDB       |     |  Y  |     |   N  |    |
| DynamoDB      |     |  Y  |     |   /  |    |
| Riak KV       |     |  Y  |     |   /  |    |
| Cassandra     |  C  |     |     |   /  |    |
| Elasticsearch | Js  |  Y  |     |   /  |    |
| Datomic       | Jv  |     |     |      |    |
| Couchbase     |     |     |  Y  |      |    |
| Redis         | Lua |  /  |  Y  |   Y  |    |
| Memcached     |     |     |  Y  |   Y  |    |
| VoltDB        | sQL |     |  Y  |   Y  |    |
| MemSQL        |  Y  |     |  Y  |   Y  |    |
| Aerospike     |     |     |  Y  |      |    |
| MonetDB       |  Y  |     |     |      |    |
| Redshift      | sQL |     |     |      |    |
| HBase         |     |     |     |      |  Y |
| Riak TS       |     |     |     |      |  Y |

### MySQL
Often used in large sharded production environments.

### MySQL/TokuDB
Online schema changes, tunable write flushing, write througput.

### PostgreSQL
Features approach document and moderate wide-column uses.

### Aurora
MySQL protocol. Easy scaling and failover. Higher write throughput.

### MongoDB
Cloudant is hosted + search.

### MongoDB/TokuMX

### CockroachDB
PostgreSQL protocol*.

### Cassandra
Column family store. CQL. High-thoughput.

### Riak KV
2.x has rich datatypes. Solr search. Per-bucket consistency config.

### MemSQL
MySQL protocol.

### Datomic
Log-structured. Immutable time-relative information. Query nodes.

### MonetDB
Columnar store.

### Redshift
PostgreSQL protocol*. Columnar store. AWS Hosted. Proprietary.

