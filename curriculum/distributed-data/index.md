---
layout: course
title: Distributed Data
category: distributed-data
tags: Merkle-DAGs
---
Merkle DAGS & Content Addressable Data

## Overview

On the centralized web, data accumulate in centralized databases.  Whoever controls those databases are responsible for enduring the information remains available, deciding how to structure the data, controlling who can edit the data, etc. On the decentralized web, the data are spread across the entire web, with many peers sharing the burden of storing, serving, and modifying content.

Content digest hashes (ie. SHA1 hashes) and Merkle DAGs (aka. Hash Trees) are the central structures or technologies that make it possible for us to maintain data in this distributed context. This course allows you to understand those technologies and shows how they are used in technologies like Git, bitcoin, and bit Torrent.  It also provides a foundation for understanding how these technologies allow us to create a content-addressable web.

## Key Concepts

* Content Digest Hashes
* Data Integrity: Using Hashes to Validate Content
* Hash Tables: Using Hash Tables to distribute data in pieces and validate it
* Hash Trees (aka Merkle DAGs)
* Why we call Hash Trees "Merkle DAGs"
* Blockchains: distributed databases that use Merkle DAGs
* Context: Database Replication - Background, CAP Theorem, Existing Technologies
* Data structures: the content in the blocks. Tabular(Relational, Key-Value), Binary Formats
* How Hash Tables and Hash Trees are used in Bit Torrent, Git, BitCoin, hypercore/dat

## Learning Objectives

* Create Hash Digests for any content
* Explain how Hash Digests allow us to verify content integrity
* Define Hash Trees and Merkle DAGs
* Demonstrate how to put data in a Merkle DAG
* Describe ways to put tabular data into a Merkle DAG
* Distinguish the different ways that Bit Torrent, Git, BitCoin, and hypercore/dat use Hash Tables and Hash Trees
* Explain the Content Addressable Web and its relation to the existing world wide web
* Illustrate how Merkle DAGs apply to creating a Content Addressable Web
* Recognize the benefits of distributed data
* Describe the challenges of maintaining data in a distributed web

# Modules

1. _TODO_: [Building DAGs](modules/building-dags)
1. **[Putting Data Into DAGs](modules/putting-data-into-dags)**
1. _TODO_: [Building a Content Addressable Web](modules/content-addressable-web)
1. _TODO_: [Tabular Data In DAGs](modules/tabular-data-in-dags)
