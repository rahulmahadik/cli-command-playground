# PostgreSQL Commands Cheatsheet

> PostgreSQL is an advanced open-source relational database. Work with powerful queries and rich data types.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `psql` | Connect to a PostgreSQL database |
| `psql -c` | Execute a single SQL command |
| `psql -f` | Execute commands from a SQL file |
| `\conninfo` | Display current connection information |
| `\l` | List all databases |
| `\dt` | List tables in the current database |
| `\d` | Describe a table structure |
| `\du` | List all roles and users |
| `\c` | Connect to a different database |
| `\q` | Quit the psql client |
| `\dn` | List all schemas |
| `\di` | List all indexes |
| `\df` | List all functions |
| `\?` | Show psql command help |
| `\x` | Toggle expanded display mode |
| `\timing` | Toggle query execution timing display |
| `CREATE DATABASE` | Create a new database |
| `DROP DATABASE` | Delete an existing database |
| `createdb` | Create a database from the shell |
| `dropdb` | Delete a database from the shell |
| `ALTER DATABASE` | Modify database properties |
| `CREATE TABLE` | Create a new table |
| `DROP TABLE` | Delete an existing table |
| `ALTER TABLE` | Modify table structure |
| `TRUNCATE` | Remove all rows from a table |
| `CREATE INDEX` | Create an index on a table |
| `DROP INDEX` | Remove an index from a table |
| `CREATE USER` | Create a new database user |
| `DROP USER` | Delete a database user |
| `CREATE ROLE` | Create a new database role |
| `GRANT` | Grant privileges to a user or role |
| `REVOKE` | Revoke privileges from a user or role |
| `ALTER USER` | Modify user account properties |
| `\copy FROM` | Import data from a file into a table |
| `\copy TO` | Export data from a table to a file |
| `COPY` | Server-side data import and export |
| `pg_dump` | Dump a database to a backup file |
| `pg_dumpall` | Dump all databases to a backup file |
| `pg_restore` | Restore a database from a backup |
| `pg_basebackup` | Take a base backup of a cluster |
| `SELECT` | Query data from tables |
| `INSERT` | Insert new rows into a table |
| `UPDATE` | Modify existing rows in a table |
| `DELETE` | Remove rows from a table |
| `EXPLAIN` | Show the query execution plan |
| `BEGIN` | Start a transaction block |
| `VACUUM` | Reclaim storage and update statistics |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice PostgreSQL interactively** | [Open Terminal](https://technoscripts.com/cli/postgresql/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/postgresql-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type PostgreSQL Commands](https://technoscripts.com/command-playground/typing-practice/postgresql/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
