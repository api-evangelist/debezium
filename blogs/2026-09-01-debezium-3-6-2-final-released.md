---
title: "Debezium 3.6.2.Final Released"
url: "https://debezium.io/blog/2026/09/01/debezium-3-6-2-final-released/"
date: "2026-09-01"
author: "Chris Cranford"
feed_url: "https://debezium.io/blog.atom"
---
As summer winds down, we’re pleased to announce Debezium 3.6.2.Final , a maintenance release packed with correctness, performance, and security improvements across the entire connector family. Among the highlights, incremental snapshots now work on PostgreSQL read-only replicas, and a fix to Debezium’s internal caching keeps long-running connectors from gradually losing throughput. On the security front, Debezium Server now masks passwords in its logs, and the PostgreSQL JDBC driver has been bumped to 42.7.13 to address CVE-2026-54291.
