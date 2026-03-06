# MongoDB Commands Cheatsheet

> MongoDB is a document-oriented NoSQL database. Query and manage collections with flexible document queries.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `mongosh` | Connect to a MongoDB instance |
| `exit` | Exit the MongoDB shell |
| `db.getMongo()` | Get the current connection object |
| `use` | Switch to a different database |
| `show dbs` | List all databases |
| `db` | Show the current database name |
| `db.dropDatabase()` | Drop the current database |
| `db.stats()` | Show database statistics |
| `show collections` | List all collections in the database |
| `db.createCollection()` | Create a new collection |
| `db.collection.drop()` | Drop a collection |
| `db.collection.stats()` | Show collection statistics |
| `db.collection.renameCollection()` | Rename a collection |
| `insertOne()` | Insert a single document |
| `insertMany()` | Insert multiple documents |
| `bulkWrite()` | Perform bulk write operations |
| `find()` | Query documents in a collection |
| `findOne()` | Find a single matching document |
| `countDocuments()` | Count documents matching a filter |
| `find().limit()` | Limit the number of results |
| `find().sort()` | Sort query results |
| `find().skip()` | Skip a number of results |
| `distinct()` | Get distinct values for a field |
| `updateOne()` | Update a single matching document |
| `updateMany()` | Update all matching documents |
| `replaceOne()` | Replace a single document entirely |
| `findOneAndUpdate()` | Find and update a document atomically |
| `deleteOne()` | Delete a single matching document |
| `deleteMany()` | Delete all matching documents |
| `findOneAndDelete()` | Find and delete a document atomically |
| `createIndex()` | Create an index on a collection |
| `getIndexes()` | List all indexes on a collection |
| `dropIndex()` | Drop an index from a collection |
| `createIndexes()` | Create multiple indexes at once |
| `aggregate()` | Run an aggregation pipeline |
| `$match` | Filter documents in aggregation |
| `$group` | Group documents by a field |
| `$project` | Shape output documents in aggregation |
| `$lookup` | Perform a left outer join |
| `$unwind` | Deconstruct an array field |
| `$sort` | Sort documents in aggregation |
| `$limit` | Limit results in aggregation |
| `db.serverStatus()` | Show server status information |
| `db.createUser()` | Create a new database user |
| `db.getUsers()` | List all users in the database |
| `rs.status()` | Show replica set status |
| `db.currentOp()` | Show currently running operations |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice MongoDB interactively** | [Open Terminal](https://technoscripts.com/cli/mongodb-shell/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/mongodb-shell-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type MongoDB Commands](https://technoscripts.com/command-playground/typing-practice/mongodb-shell/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
