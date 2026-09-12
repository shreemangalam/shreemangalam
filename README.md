# Shree Mangalam Singh

Software engineer working on enterprise integrations and backend systems.

I work at **Strada**, building and supporting SAP integrations that connect employee data with payroll and benefits platforms. Outside work, I build projects in **Go** and **Java/Spring Boot** to explore storage, source-code analysis, and failure recovery.

I'm interested in how systems behave when data changes, messages fail, or a process stops unexpectedly, and how to make that behavior easier to inspect and test.

[Portfolio](https://shreemangalam-singh.vercel.app/) · [Technical writing](https://shreemangalam-singh.vercel.app/blog) · [LinkedIn](https://www.linkedin.com/in/shreemangalam) · [Email](mailto:shreemangalamsingh29@gmail.com)

## Selected projects

### [KEG](https://github.com/shreemangalam/keg)

**Completed · Go, Next.js, Playwright**

A Bitcask-style key-value storage engine with append-only records, an in-memory index, compaction, and backup/restore. Its browser console exposes data files, record offsets, and index updates so the storage lifecycle can be inspected directly.

The case study explains the architecture and trade-offs. Separate evidence includes a recorded demo, recovery tests, race-detection results, and benchmarks with their limitations.

[Read the case study](https://shreemangalam-singh.vercel.app/blog/building-keg-storage-engine) · [Demo and test evidence](https://shreemangalam-singh.vercel.app/projects/keg/evidence)

### [Stratum](https://github.com/shreemangalam/stratum)

**Completed · Go, TypeScript, Next.js, PostgreSQL, Docker**

A structural diff tool that compares source code through syntax trees rather than lines alone. It matches nodes across versions and produces edit scripts describing changes such as moves and renames. It also includes three-way structural merge and cross-file move detection.

### [Faultline](https://github.com/shreemangalam/faultline)

**In progress · Java, Spring Boot, PostgreSQL, Docker**

An integration failure simulator and recovery control plane. I'm building it to explore how failures propagate across SAP-connected systems, how recovery order depends on downstream health, and how failed events can be reprocessed safely.

## Professional experience

**Strada · Associate Integration Consultant**  
April 2026 to present · Previously Integration Consultant, September 2024 to March 2026

- Deliver SAP CPI integrations from requirements and design through testing, go-live, and production support.
- Connect SuccessFactors with payroll and benefits systems using REST, SOAP, and OData.
- Build Groovy/XSLT transformations and reusable patterns for validation, data masking, and exception handling.
- Improve failed-message handling with JMS-based retries, structured errors, and monitoring.

## Technical stack

- **Professional integration work:** SAP Integration Suite/CPI, SuccessFactors, Groovy, XSLT, JMS, REST, SOAP, OData.
- **Backend and systems projects:** Go, Java, Spring Boot, PostgreSQL.
- **Interfaces and tooling:** TypeScript, React, Next.js, Docker, Git, Playwright.

## Current focus

I'm practicing data structures and algorithms in Java, focusing on problem-solving, time and space complexity, and choosing appropriate data structures.

I'm deepening my backend engineering work through Faultline, with particular attention to retry behavior, dependency-aware recovery, and tests that exercise failure paths. My longer-term interests are storage systems, event-driven architecture, and distributed systems.
