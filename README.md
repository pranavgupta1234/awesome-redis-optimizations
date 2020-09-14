# Awesome Redis Optimizations [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome guides, case studies, tutorials and tools for optimizing your redis deployment

## Contents

- [Guides/Tools/Case Studies](#guidestoolscase-studies)
  - [Memory Optimization](#memory-optimization)
- [Tools/Repositories](#toolsrepositories)


## Memory Optimization

- [RedisLabs' Advice](https://docs.redislabs.com/latest/ri/memory-optimizations/) - Advice from the home of Redis
- [Instagram's Key-Value pairs](https://instagram-engineering.com/storing-hundreds-of-millions-of-simple-key-value-pairs-in-redis-1091ae80f74c) - How Instagram team stored 300 million key value pairs in redis with least memory
- [Redis hash-max-ziplist-entries configuration](https://www.peterbe.com/plog/understanding-redis-hash-max-ziplist-entries) - How hash-max-ziplist-entries configuration affects storage space for hashes


## Tools/Repositories

- [rdbtools](https://github.com/sripathikrishnan/redis-rdb-tools) - Memory profiling for redis data and a parser for dump.rdb files