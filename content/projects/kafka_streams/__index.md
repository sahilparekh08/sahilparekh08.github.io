---
title: "Kafka Streams Application"
description: "Developed a Java-based application demonstrating stream processing with Kafka"
date: "2024-03-01"
---

This is a Java based application demonstrating stream processing applications using Kafka. The app consists of a bash script giving the user flexibility to spin up their own Apache Kafka cluster with configurable number of machines, replicatino factor and the ability to create their own topics. It also provides the users a Producer and Consumer API, the ability to read PDF files word by word using Apache PDFBox. Gradle is used for dependency management. The application shows a word count example utilizing a sliding window property of streams and fetching the top N highest occuring non-ordinary and ordinary (articles, pronouns, prepositions, etc) words in a collection of PDF files.

GitHub Repo: [Kafka-Streams-App](https://github.com/sahilparekh08/Kafka-Streams-App)

Refernces:
1. [Kafka: a Distributed Messaging System for Log Processing](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.microsoft.com/en-us/research/wp-content/uploads/2017/09/Kafka.pdf) by Jay Kreps, Neha Narkhede, Jun Rao; NetDB workshop '11, 2011
2. [Streams and Tables: Two Sides of the Same Coin](https://dl.acm.org/doi/10.1145/3242153.3242155) by Matthias J. Sax, Guozhang Wang, Matthias Weidlich, Johann-Christoph Freytag; BIRTE '18: Proceedings of the International Workshop on Real-Time Business Intelligence and Analytics, 2018
3. https://kafka.apache.org/37/documentation/streams/core-concepts
4. https://kafka.apache.org/20/documentation/streams/developer-guide/dsl-api.html