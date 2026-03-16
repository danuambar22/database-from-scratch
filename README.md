# Database from Scratch

Building a simple database engine from the ground up in C — no libraries, no frameworks, just raw systems programming.

## Goal

Implement the core components of a relational database to understand how databases work under the hood:

- **Storage Engine** — Page-based file I/O for persistent data
- **B-Tree Index** — Efficient key lookup and range queries
- **SQL Parser** — Basic SQL command parsing (SELECT, INSERT, CREATE TABLE)
- **Query Executor** — Translating parsed queries into storage operations

## Tech Stack

- **Language:** C
- **Build:** GCC / Make
- **No external dependencies**

## Status

Early development — architecture and initial implementation in progress.

## Roadmap

- [ ] REPL (Read-Eval-Print Loop)
- [ ] In-memory row storage
- [ ] Persistence to disk (pager)
- [ ] B-Tree index structure
- [ ] Basic SQL parsing (INSERT, SELECT)
- [ ] Table creation and schema management
- [ ] Cursor abstraction for table traversal

## Inspiration

- [SQLite Architecture](https://www.sqlite.org/arch.html)
- [Let's Build a Simple Database](https://cstack.github.io/db_tutorial/)
