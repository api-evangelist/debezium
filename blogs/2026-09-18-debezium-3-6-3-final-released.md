---
title: "Debezium 3.6.3.Final Released"
url: "https://debezium.io/blog/2026/09/18/debezium-3-6-3-final-released/"
date: "2026-09-18"
author: "Chris Cranford"
feed_url: "https://debezium.io/blog.atom"
---
We’re pleased to announce Debezium 3.6.3.Final , a maintenance release focused on stability and reliability improvements. The Oracle connector receives the most attention in this release, with corrected savepoint partial rollback handling for tables with LOB columns, a fix for unbounded mining sessions with the log-count mining algorithm, and ORA-02002 now treated as a retriable error so the connector can recover from failovers. The MySQL and MariaDB connectors once again restart automatically after transient communication errors, while the SQL Server, Vitess, and Informix connectors pick up t
