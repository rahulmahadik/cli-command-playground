# MySQL Commands Cheatsheet

> MySQL is an open-source relational database. Query, manage, and administer the world's most-used web database.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `\G` | Display results in vertical format |
| `source` | Execute SQL statements from a file |
| `\c` | Cancel the current input statement |
| `\s` | Display server status information |
| `DELIMITER` | Change the statement delimiter |
| `tee` | Log output to a file |
| `mysqldump --single-transaction` | Dump database with consistent snapshot |
| `mysqldump --all-databases` | Dump all databases on the server |
| `mysqldump --routines` | Include stored routines in dump |
| `mysqldump --no-data` | Dump only the table structure |
| `mysqldump --master-data` | Include binary log coordinates |
| `mysqldump --where` | Dump rows matching a condition |
| `mysql < backup.sql` | Restore a database from backup file |
| `mysqladmin ping` | Check if the server is alive |
| `mysqladmin processlist` | Show active server connections |
| `mysqladmin kill` | Kill a running server thread |
| `mysqladmin flush-privileges` | Reload the grant tables |
| `mysqladmin status` | Show brief server status |
| `mysqladmin -i` | Repeat status at intervals |
| `CREATE USER` | Create a new database user account |
| `GRANT` | Grant privileges to a user |
| `REVOKE` | Remove privileges from a user |
| `SHOW GRANTS` | Display privileges for a user |
| `ALTER USER` | Modify a user account |
| `CREATE ROLE` | Create a named collection of privileges |
| `SHOW CREATE TABLE` | Display the CREATE TABLE statement |
| `SHOW PROCESSLIST` | Show active connections and queries |
| `SHOW STATUS` | Display server status variables |
| `SHOW ENGINE INNODB STATUS` | Display InnoDB engine diagnostics |
| `SHOW INDEX` | Display index information for a table |
| `EXPLAIN` | Show the query execution plan |
| `EXPLAIN ANALYZE` | Run and show actual execution stats |
| `ANALYZE TABLE` | Update table statistics for optimizer |
| `OPTIMIZE TABLE` | Reclaim unused space and defragment |
| `sys.schema_unused_indexes` | Find unused indexes in the schema |
| `CHANGE REPLICATION SOURCE TO` | Configure replication source settings |
| `START REPLICA` | Start the replication process |
| `SHOW REPLICA STATUS` | Display replication status details |
| `gtid_mode` | Enable GTID-based replication |
| `SHOW BINARY LOGS` | List all binary log files |
| `mysqlbinlog` | Process binary log files |
| `PURGE BINARY LOGS` | Remove old binary log files |
| `FLUSH BINARY LOGS` | Close and open a new binary log |
| `LOAD DATA INFILE` | Load data from a file into a table |
| `mysqlimport` | Import data from text files |
| `SELECT INTO OUTFILE` | Export query results to a file |
| `mysqlpump` | Parallel database backup utility |
| `mysqlcheck` | Check, repair, and optimize tables |
| `mysqlshow` | Display database and table information |
| `mysql_secure_installation` | Improve MySQL installation security |
| `mysqldumpslow` | Summarize slow query log entries |
| `START TRANSACTION` | Begin a new transaction |
| `COMMIT` | Save transaction changes permanently |
| `ROLLBACK` | Undo transaction changes |
| `SAVEPOINT` | Set a named transaction savepoint |
| `FOR UPDATE` | Lock selected rows for update |
| `SET TRANSACTION ISOLATION LEVEL` | Set the transaction isolation level |
| `innodb_buffer_pool_size` | Configure InnoDB buffer pool memory |
| `ALTER TABLE ENGINE=InnoDB` | Convert a table to InnoDB engine |
| `SET PERSIST` | Set and persist a server variable |
| `\js` | Switch MySQL Shell to JavaScript mode |
| `\connect` | Connect to a MySQL server instance |
| `util.dumpInstance()` | Dump the entire MySQL instance |
| `\watch` | Repeat a query at intervals |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice MySQL interactively** | [Open Terminal](https://technoscripts.com/cli/mysql/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/mysql-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type MySQL Commands](https://technoscripts.com/command-playground/typing-practice/mysql/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
