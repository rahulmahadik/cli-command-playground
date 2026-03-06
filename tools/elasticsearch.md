# Elasticsearch Commands Cheatsheet

> Elasticsearch is a distributed search and analytics engine.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `GET _cluster/health` | Check cluster health status |
| `GET _cluster/stats` | Get cluster-wide statistics |
| `GET _cluster/settings` | View cluster settings |
| `PUT _cluster/settings` | Update cluster settings |
| `GET _cat/nodes` | List cluster nodes |
| `PUT /index_name` | Create a new index |
| `DELETE /index_name` | Delete an index |
| `GET _cat/indices` | List all indices |
| `POST /index_name/_open` | Open a closed index |
| `POST /index_name/_close` | Close an index |
| `GET /index_name/_settings` | View index settings |
| `PUT /index_name/_settings` | Update index settings |
| `POST /index/_doc` | Index a new document |
| `PUT /index/_doc/id` | Index or replace a document by ID |
| `GET /index/_doc/id` | Retrieve a document by ID |
| `DELETE /index/_doc/id` | Delete a document by ID |
| `POST /index/_update/id` | Partially update a document |
| `POST /index/_bulk` | Perform bulk indexing operations |
| `POST _mget` | Retrieve multiple documents at once |
| `POST /index/_delete_by_query` | Delete documents matching a query |
| `GET /index/_search` | Search documents in an index |
| `GET /index/_search (match)` | Full-text match query |
| `GET /index/_search (bool)` | Boolean compound query |
| `GET /index/_search (range)` | Range-based query |
| `GET /index/_search (term)` | Exact term query |
| `GET /index/_count` | Count documents matching a query |
| `GET /index/_search (highlight)` | Search with highlighted results |
| `GET /index/_search (sort)` | Search with custom sorting |
| `GET /index/_mapping` | View index field mappings |
| `PUT /index/_mapping` | Define or update field mappings |
| `POST _analyze` | Analyze text with an analyzer |
| `GET /index/_field_caps` | Get field capabilities |
| `GET /index/_search (terms agg)` | Terms aggregation query |
| `GET /index/_search (date_histogram)` | Date histogram aggregation |
| `GET /index/_search (avg/sum/min/max)` | Metric aggregations |
| `GET /index/_search (nested agg)` | Nested aggregation query |
| `PUT _snapshot/repo_name` | Register a snapshot repository |
| `PUT _snapshot/repo/snap` | Create a snapshot |
| `POST _snapshot/repo/snap/_restore` | Restore from a snapshot |
| `GET _snapshot/repo/_all` | List all snapshots |
| `GET _cat/shards` | List shard allocation |
| `GET _cat/allocation` | Show disk allocation per node |
| `POST _cluster/reroute` | Manually reroute shards |
| `GET _nodes/stats` | Get node-level statistics |
| `POST _aliases` | Manage index aliases |
| `GET _alias/alias_name` | View an alias definition |
| `POST _reindex` | Reindex documents from one index to another |
| `PUT _ilm/policy/policy_name` | Create an index lifecycle policy |
| `PUT _security/user/username` | Create or update a user |
| `PUT _security/role/rolename` | Create or update a role |
| `GET _security/_authenticate` | Check the authenticated user |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Elasticsearch interactively** | [Open Terminal](https://technoscripts.com/cli/elasticsearch/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/elasticsearch-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Elasticsearch Commands](https://technoscripts.com/command-playground/typing-practice/elasticsearch/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
