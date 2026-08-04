---
title: "Running the Debezium Platform on AWS: PostgreSQL to Amazon Kinesis"
url: "https://debezium.io/blog/2026/07/24/debezium-platform-on-aws-postgres-to-kinesis/"
date: "2026-07-24"
author: "Philippe Camus"
feed_url: "https://debezium.io/blog.atom"
---
In his recent mid-year update , Mario highlighted the incredible work he and his team have done to make the Debezium Platform operational on Kubernetes. So let us take it somewhere concrete: Amazon Web Services . This post stands the Platform up on a single-node k3s cluster on an EC2 instance and builds a real change-data-capture pipeline from Amazon RDS for PostgreSQL to Amazon Kinesis .
