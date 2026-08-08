---
title: "Debezium 3.6.1.Final Released"
url: "https://debezium.io/blog/2026/08/04/debezium-3-6-1-final-released/"
date: "2026-08-04"
author: "Chris Cranford"
feed_url: "https://debezium.io/blog.atom"
---
We’re pleased to announce the release of Debezium 3.6.1.Final , a maintenance release that delivers important data integrity and security improvements across multiple connectors. This release fixes several issues that could affect change event accuracy, including correct parsing of BC-era dates in PostgreSQL, proper mapping of MySQL INTEGER UNSIGNED columns, and resolution of Oracle RowId corruption in change events. The JDBC sink connector also receives a fix for tsvector data handling, and credential leakage has been addressed in log output and configuration serialization.
