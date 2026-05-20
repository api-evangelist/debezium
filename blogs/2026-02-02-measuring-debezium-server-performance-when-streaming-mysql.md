---
title: "Measuring Debezium Server performance when streaming MySQL to Kafka"
url: "https://debezium.io/blog/2026/02/02/measuring-debezium-server-performance-mysql-streaming/"
date: "2026-02-02T00:00:00+00:00"
author: "Alvar Viana"
feed_url: "https://debezium.io/feed"
---
Performance is a critical concern when implementing Change Data Capture (CDC) solutions in production environments. In this post, I am going to share how we have measured Debezium Server performance (deployed in a Docker container) while streaming changes from MySQL to Kafka. All of this with the default configurations for Debezium, MySQL and Kafka.
