# distributed datastores

| Name          | *QL | Doc | Mem | C.Rd | t |   Note                                                              |
| ------------- | --- |     |     | ---- | - |   ----------------------------------------------------------------- |
| MySQL         |  Y  |     |     |   Y  |   |   Often used in large sharded production environments.              |
| MySQL/TokuDB  |  Y  |     |     |   Y  |   |   Online schema changes, tunable write flushing, write througput.   |
| PostgreSQL    |  Y  |     |     |   Y  |   |   Features approach document and moderate wide-column uses.         |
| CitusData     |  Y  |     |     |      |   |                                                                     |
| Aurora        |  Y  |     |     |   Y  |   |   Easy scaling and failover, higher write throughput.               |
| CockroachDB   | sQL |     |     |   Y  |   |                                                                     |
| MongoDB       |     |  Y  |     |      |   |                                                                     |
| MongoDB/TokuMX|     |  Y  |     |      |   |                                                                     |
| RethinkDB     |     |  Y  |     |      |   |                                                                     |
| CouchDB       |     |  Y  |     |   N  |   | Cloudant is hosted + search.                                        |
| DynamoDB      |     |  Y  |     |   /  |   |                                                                     |
| Riak KV       |     |  Y  |     |   /  |   | 2.x has rich datatypes. Solr search. Per-bucket consistency config. |
| Cassandra     |  C  |     |     |   /  |   | Column family store. CQL. High-thoughput.                           |
| Elasticsearch | Js  |  Y  |     |   /  |   |                                                                     |
| Datomic       | Jv  |     |     |      |   | Log-structured. Immutable time-relative information. Query nodes.   |
| Couchbase     |     |     |  Y  |      |   | Low-latency.                                                        |
| Redis         | Lua |  /  |  Y  |   Y  |   | Low-latency.                                                        |
| Memcached     |     |     |  Y  |   Y  |   | Low-latency.                                                        |
| VoltDB        | sQL |     |  Y  |   Y  |   | Low-latency.                                                        |
| MemSQL        |  Y  |     |  Y  |   Y  |   |                                                                     |
| Aerospike     |     |     |  Y  |      |   |                                                                     |
| MonetDB       |  Y  |     |     |      |   | Columnar store.                                                     |
| Redshift      | sQL |     |     |      |   | Columnar store.                                                     |
| HBase         |     |     |     |      | Y |                                                                     |
| Riak TS       |     |     |     |      | Y |                                                                     |
