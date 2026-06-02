---
title: "Migrating MySQL Connector to Oracle’s Official ANTLR Grammar"
url: "https://debezium.io/blog/2026/05/10/mysql-grammar-migration/"
date: "2026-05-10"
author: "Vincenzo Santonastaso"
feed_url: "https://debezium.io/feed"
---
When I started working on migrating Debezium’s MySQL connector from the Positive Technologies grammar to Oracle’s official MySQL grammar, I honestly thought it would be straightforward. " Just replace the grammar files and fix a few tests, right? " Well, turns out parsing DDL is like opening a Matryoshka doll, every layer reveals a smaller, even trickier one inside.
