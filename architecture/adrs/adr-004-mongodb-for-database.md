## ADR 004: MongoDB for Database

## Context
VChart requires a secure, compliant, scalable, and high-performance database to store various types of medical data, including patient records, AI-generated medical charts, speech-to-text transcriptions, and user authentication data. Given the nature of AI-driven documentation, where structured and unstructured data formats vary, a flexible schema is essential. Traditional SQL databases like PostgreSQL provide strong ACID compliance, but they may not be the best fit for dynamic, evolving AI-generated medical notes. MongoDB, as a NoSQL document database, offers a schema-flexible structure, horizontal scalability, and fast query performance, making it a strong choice for handling AI-processed medical documentation.

### Options
MongoDB, Firebase, PostgreSQL

## Decision
We will use MongoDB as our database because
- Flexible Data Model → AI-generated medical notes can vary in structure.
- JSON-Based Storage → Works well with Next.js.
- Scalable → Supports high read & write workloads (critical for medical charts).
- Fast Querying → Easily handles real-time chart updates & voice-to-text logs.
- Sharding for Performance → Can distribute medical records across multiple nodes for redundancy.

## Status
Accepted.

## Consequences
Using MongoDB requires specific security measures to ensure compliance with HIPAA, PHIPA, and SOC 2 regulations. Encryption at rest and in transit must be enforced using MongoDB Enterprise Transparent Data Encryption (TDE) and TLS/SSL. Access control must be implemented via role-based access control (RBAC), restricting permissions for nurses, doctors, and administrators. Another key reason for selecting MongoDB is that our team is more familiar with MongoDB than relational databases like PostgreSQL, which will result in faster development, easier debugging, and more efficient collaboration.