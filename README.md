# Redis-Vs-Memcached


# Choosing between Redis and Memcached
| Feature | Redis | Memcached |
| ------ | ------ | ------ |
| Description | In-memory data structure store, used as database, cache and message broker | In-memory key-value store, originally intended for caching	 |
| Read/write speed | Faster Than Memcached | Fast |
| Memory usage (100,000 ~2KB strings (~200MB)) | After flusihng dropped to ~29MB | stayed at ~225MB |
| Advanced data structures | YES (lists, sets, sorted sets, hashes, bit arrays) | No (Strings only) |
| Multithreaded architecture | YES | NO |
| key/value pairs LIMIT | up to 512MB | string up to 1MB |
| Persistence | Handle persistent data and Syncs data to disk every 2 seconds. | Lost data when restart |
| Replication | Support master-slave replication | Doesn't support replication  |




## References
*  [Alibaba Medium](https://medium.com/@Alibaba_Cloud/redis-vs-memcached-in-memory-data-storage-systems-3395279b0941)
*  [AWS](https://aws.amazon.com/elasticache/redis-vs-memcached/)
*  [Stackoverflow](https://stackoverflow.com/questions/10558465/memcached-vs-redis)
*  [Db engines](https://db-engines.com/en/system/Redis#a33)
*  [Caching](https://medium.com/datadriveninvestor/all-things-caching-use-cases-benefits-strategies-choosing-a-caching-technology-exploring-fa6c1f2e93aa)
*  [Intro caching](https://dzone.com/articles/introducing-amp-assimilating-caching-quick-read-fo)
