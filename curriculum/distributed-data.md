---
layout: page
title: Distributed Data
categories: Merkle-DAGs distributed-data
---
Merkle DAGS & Content Addressable Data

## What is a Merkle DAG?
A Merkle DAG is a tree of Cryptographic hashes. What does that mean?

*TODO*: _Cryptographic Hashes_ What does it mean to calculate a Hash Digest of content (ie. SHA1 or md5) and how can we use them to verify data integrity?

*TODO*: _Trees of Hashes_ What is a Hash Tree (aka Merkle DAG) and why is it useful?

## What does it mean to put data in a Merkle DAG?

**[Replicating files](/distributed-web-primer/presentations/How Bit Torrent Replicates Files)**: How bit torrent uses hash tables to replicate files
while maintaining data integrity

 *TODO*: _Hash Trees (Merkle DAGs), Hash Tables and DHTs_ By default, Bit Torrent uses a Distributed Hash Table, not Hash Trees (Merkle DAGs). What's the difference? When does it matter?

**[Replicating changes to files and directories](/distributed-web-primer/presentations/How Hypercore Replicates Changes to Files)**: How hypercore Uses Merkle DAGs to Replicate Files that Change Over Time  

**[Git commits, trees and blobs](/distributed-web-primer/presentations/How Git Stores Data)**: How Git Uses Merkle DAGs to represent files, directories, and the history of changes to that those files & directories.

*TODO*: _Replicating ledgers as Blockchains_: How blockchain technologies like bitCoin and ethereum use Merkle DAGs to distribute ledgers of transactions.  

## Building a Content Addressable Web

*TODO*: _What Does Content Addressable Mean?_ What is a Content Addressable filesystem and what would a content addressable web look like?  

*TODO*: _Replacing IP addresses with Merkle DAGs_ ipfs aims to replace the global ip address system with Merkle DAGs. What does that mean?  

## Benefits of Distributed Data

*TODO*: _Git-enabled Collaboration Workflows_ How distributed version control systems like Git and Mercurial enable richer forms of collaboration that are more productive, more flexible, and more transparent.

## Current work: Tabular Data in Merkle DAGs

These presentations are relevant to the current work of the [Dat Jawn project](http://datjawn.com).

**[Storing Tabular Data in a DAG](/distributed-web-primer/presentations/Storing Tabular Data in a DAG)**: Building on an understanding of [how Git represents commits, trees and blobs](/distributed-web-primer/presentations/How Git Stores Data), this presentation outlines a strategy for storing tabular data in a DAG

Side-considerations:

* [Problems with Replicating Raw DB Tables](/distributed-web-primer/presentations/Problems with Replicating Raw DB Tables)
* [Replicating Log-Structured Databases](/distributed-web-primer/presentations/Replicating Log Structured Databases)
