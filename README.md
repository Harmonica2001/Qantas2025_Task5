# Qantas Flight Scheduling – Neo4j Migration

Relational (SQLite) to graph (Neo4j) migration for the Qantas flight scheduling database.

| File | Contents |
|---|---|
| `import.txt` | Task 2 – Cypher scripts: constraints, node imports, relationship imports, indexes, validation |
| `queries.txt` | Task 3 – Four Cypher query use cases (with expected results) |
| `csv/` | The 15 CSV files exported from the relational database |

## How to run
1. Copy all files from `csv/` into the Neo4j instance's `import` folder.
2. Run the statements in `import.txt` in order (Parts A–F) in Neo4j Browser / Query.
3. Expected result: 79 nodes, 103 relationships, 0 orphan tickets.
4. Run each query in `queries.txt` separately.

Tested on Neo4j Desktop, Cypher 25.
