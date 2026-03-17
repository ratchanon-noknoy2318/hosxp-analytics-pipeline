# HOSxP Analytics Pipeline

SQL-based analytics pipeline for legacy HOSxP hospital databases.

Processes operational data covering 400K+ patient records and reduces reporting latency from ~24 hours to <1 hour.

## Problem

HOSxP operational data is difficult to analyze due to undocumented schemas and complex multi-table relationships.

Generating cross-department reports previously required up to 24 hours.

## Architecture

```
HOSxP MySQL
  ↓
SQL ETL Queries
  ↓
Optimized Analytics Queries
  ↓
Operational Dashboard
```

## Tech Stack

- MySQL
- SQL

## Project Structure

```
Database/   schema definitions
SQL/        ETL and analytics queries
```

## License

MIT
