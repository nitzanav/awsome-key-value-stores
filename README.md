# Awsome Key Value Stores (persisted and in-memory)

|Link|Statement|Persisted / In-memory|Language|
:-----:|:-----:|:-----:|:-----:
[Redis](https://github.com/antirez/redis)|Redis is an in-memory database that persists on disk. The data model is key-value, but many different kind of values are supported: Strings, Lists, Sets, Sorted Sets, Hashes, HyperLogLogs, Bitmaps, Streams !! New!!.|In-memory (Persistent is not its "forte")|
[memcache](https://github.com/memcached/memcached)| |In-memory|
[Aerospike](https://github.com/aerospike/aerospike-server)|Aerospike Database Server – flash-optimized, in-memory, nosql database|In-memory|
[LMDB](http://symas.com/mdb/)|||C
[LevelDB](https://github.com/syndtr/goleveldb)|LevelDB key/value database in Go.||
[rocksdb](https://github.com/facebook/rocksdb)|Embedded key-value store for fast storage by Facebook http://rocksdb.org|Persisted|
[LedisDB](http://ledisdb.com)|A high performance NoSQL like Redis powered by Go.|Depends on Backed|
[ssdb](https://github.com/ideawu/ssdb)| A high performance NoSQL database supporting many data structures, an alternative to Redis.||C++
[bolt](https://github.com/boltdb/bolt)|An embedded key/value database for Go.|Persisted|Go
[VoltDB](https://github.com/VoltDB/voltdb/)|VoltDB is a horizontally-scalable, in-memory SQL RDBMS designed for applications that have extremely high read and write throughput requirements.|In-memory|
[AWS DynamoDB](https://aws.amazon.com/dynamodb/)|||

# Other that can be used as Key Value Stores
* [mongo](https://github.com/mongodb/mongo)
* [cassandra](https://github.com/apache/cassandra)
* [rethinkdb](https://github.com/rethinkdb/rethinkdb)
Riak is a decentralized datastore from Basho Technologies
* [Riak](https://github.com/basho/riak)

# More Info
* Ledis
  * Amazing Benckmarks Summary http://ledisdb.com
  * gives Redis protocol backed by either of those: LevelDB, goleveldb, LMDB, RocksDB, BoltDB or Memory.
  * Very Interesting Article - https://medium.com/@siddontang/build-up-a-high-availability-distributed-key-value-store-b4e02bc46e9e
