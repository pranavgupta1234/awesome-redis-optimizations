# Awesome Redis Optimizations [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome guides, case studies, tutorials and tools for optimizing your redis deployment

## Contents

- [Guides/Tools/Case Studies](#guidestoolscase-studies)
  - [Memory Optimization with Hashes](#memory-optimization-with-hashes)
  - [Pipelining in Redis](#pipelining-in-redis)
  - [Low Memory, Fast Computation, the Bitsets](#low-memory-fast-computation-the-bitsets)
  - [Lua Scripting, Kill Latency with Server Side Computation](#lua-scripting-kill-latency-with-server-side-computation)
- [Tools/Repositories](#toolsrepositories)


## Memory Optimization With Hashes

- [RedisLabs' Advice](https://docs.redislabs.com/latest/ri/memory-optimizations/) - Advice from the home of Redis
- [Instagram's Key-Value pairs](https://instagram-engineering.com/storing-hundreds-of-millions-of-simple-key-value-pairs-in-redis-1091ae80f74c) - How Instagram team stored 300 million key value pairs in redis with least memory
- [Redis hash-max-ziplist-entries configuration](https://www.peterbe.com/plog/understanding-redis-hash-max-ziplist-entries) - How hash-max-ziplist-entries configuration affects storage space for hashes


## Pipelining in Redis

- [Concept of Pipelining](https://redis.io/topics/pipelining) - Get the most out of your single redis call


## Low Memory, Fast Computation, the Bitsets

- [Realtime Metrics with low memory footprint](https://blog.getspool.com/2011/11/29/fast-easy-realtime-metrics-using-redis-bitmaps/) - How to organize data in bitsets to achieve computation of some simple realtime metrics


## Lua Scripting, Kill Latency with Server Side Computation

- [Lua's Guide for Redis Users](https://www.redisgreen.net/blog/intro-to-lua-for-redis-programmers/) - Achieve server side computation in Redis
- [Example Lua Scripts](https://www.redisgreen.net/library.html) - Basic small Lua scripts for starters


## Tools/Repositories

- [rdbtools](https://github.com/sripathikrishnan/redis-rdb-tools) - Memory profiling for redis data and a parser for dump.rdb files
- [twemproxy](https://github.com/twitter/twemproxy) - A fast, light-weight proxy for memcached and redis, helps to reduce number of connections to the caching servers on the backend. This, together with protocol pipelining and sharding enables you to horizontally scale your distributed caching architecture.
