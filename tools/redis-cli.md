# Redis Commands Cheatsheet

> Redis is an in-memory data structure store. Interact with keys, lists, sets, and streams directly.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `redis-cli` | Connect to a Redis server |
| `AUTH` | Authenticate with a password |
| `PING` | Test if the server is responsive |
| `SELECT` | Switch to a different database index |
| `QUIT` | Close the connection |
| `SET` | Set a string value for a key |
| `GET` | Get the value of a key |
| `MSET` | Set multiple key-value pairs at once |
| `MGET` | Get values of multiple keys |
| `INCR` | Increment a key's integer value by one |
| `DECR` | Decrement a key's integer value by one |
| `APPEND` | Append a value to a string key |
| `LPUSH` | Insert values at the head of a list |
| `RPUSH` | Insert values at the tail of a list |
| `LPOP` | Remove and return the first list element |
| `RPOP` | Remove and return the last list element |
| `LRANGE` | Get a range of elements from a list |
| `LLEN` | Get the length of a list |
| `SADD` | Add members to a set |
| `SMEMBERS` | Get all members of a set |
| `SISMEMBER` | Check if a value is a set member |
| `SREM` | Remove members from a set |
| `SUNION` | Return the union of multiple sets |
| `SINTER` | Return the intersection of multiple sets |
| `HSET` | Set a field value in a hash |
| `HGET` | Get a field value from a hash |
| `HGETALL` | Get all fields and values in a hash |
| `HDEL` | Delete a field from a hash |
| `HMSET` | Set multiple hash fields at once |
| `HINCRBY` | Increment a hash field integer value |
| `ZADD` | Add members to a sorted set |
| `ZRANGE` | Get members by score range |
| `ZRANK` | Get the rank of a member |
| `ZSCORE` | Get the score of a member |
| `ZREM` | Remove members from a sorted set |
| `KEYS` | Find keys matching a pattern |
| `DEL` | Delete one or more keys |
| `EXISTS` | Check if a key exists |
| `EXPIRE` | Set a key's time to live in seconds |
| `TTL` | Get the remaining TTL for a key |
| `TYPE` | Get the data type of a key |
| `SCAN` | Incrementally iterate over keys |
| `INFO` | Get server information and statistics |
| `DBSIZE` | Return the number of keys in the database |
| `FLUSHDB` | Remove all keys from the current database |
| `FLUSHALL` | Remove all keys from all databases |
| `CONFIG GET` | Get a server configuration value |
| `SAVE` | Synchronously save data to disk |
| `SUBSCRIBE` | Subscribe to a channel for messages |
| `PUBLISH` | Publish a message to a channel |
| `PSUBSCRIBE` | Subscribe to channels matching a pattern |
| `MULTI` | Begin a transaction block |
| `EXEC` | Execute all commands in a transaction |
| `DISCARD` | Discard all commands in a transaction |
| `WATCH` | Watch keys for changes before transaction |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Redis interactively** | [Open Terminal](https://technoscripts.com/cli/redis-cli/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/redis-cli-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Redis Commands](https://technoscripts.com/command-playground/typing-practice/redis-cli/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
