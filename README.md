 Snowflake Streams Practice

This repository contains my practice work on **Snowflake Streams**, focusing on understanding how **Change Data Capture (CDC)** is implemented in Snowflake to track data changes (INSERT, UPDATE, DELETE) in tables.

---

## 🚀 What I Practiced
- Created **base tables** in Snowflake.
- Implemented **Streams** to capture changes in real-time.
- Used **INSERT/UPDATE/DELETE** operations on source tables.
- Queried streams to validate captured changes.
- Combined **Streams with Tasks** for automated data processing.

---

## 📌 Key Concepts
- **Stream**: A Snowflake object that records table changes (CDC).
- **Offset Tracking**: Ensures each change is read once.
- **Usage**: Often used for ETL pipelines, auditing, or incremental loading.
