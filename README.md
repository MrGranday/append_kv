# Append-Only Key-Value Store 🦀

A simple **single-node key-value store** built in Rust using an **append-only log**.  
This project is designed for learning **storage engines, file-based persistence, and crash-safe basics**.

---

## Features ✅

- `PUT / GET` operations
- **In-memory index** using Rust’s `HashMap` for fast reads
- **Append-only log** for persistence
- Loads data from log at startup
- Simple **CLI interface** to test functionality
- Optional: checksum support for log entries

---
