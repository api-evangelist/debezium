---
title: "No More Tuning: Oracle Log Mining Simplified in Debezium 3.6"
url: "https://debezium.io/blog/2026/07/06/oracle-logminer-no-more-tuning/"
date: "2026-07-06"
author: "Chris Cranford"
feed_url: "https://debezium.io/blog.atom"
---
If you have ever deployed the Debezium Oracle connector in an environment with bursty workloads, you have probably spent more time than you would like tuning the log.mining.batch.size.* , log.mining.sleep.time.* , and log.mining.scn.gap.detection.* properties. Getting the balance right between peak and quiet periods was, frankly, a losing battle — what worked for your nightly ETL window would over-read during the day, and what worked during the day would fall hopelessly behind at night. In Debezium 3.6, we replaced this entire mechanism.
