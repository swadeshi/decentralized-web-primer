---
layout: module
title: Putting Data Into DAGs
category: decentralized-data
tags: Merkle-DAGs
---

## Prerequisites

If you are unsure about what cryptographic hashes and Merkle DAGs are, you should explore the module on [Building DAGs](../building-dags) before proceeding with this module.

## Conceptual Framework

Merkle DAGs make it possible for us to distribute data across infinitely scalable, decentralized, peer-to-peer networks.  This module explains why we use Merkle DAGs and how we put data into them. It provides examples by explaining how some well-known technologies like BitCoin, Git, and Bit Torrent structure their DAGs.

The excitement around bitcoin and blockchain technologies has made this space a bit confusing. This module includes information aimed at helping you understand the relationship between blockchains, Merkle DAGs, and the decentralized web.

## Learning Objectives

* Explain the benefits of representing data as Merkle DAGs
* Demonstrate how to put data in a Merkle DAG
* Describe ways to put tabular data into a Merkle DAG
* Distinguish the different ways that Bit Torrent, Git, BitCoin, and hypercore/dat use Hash Tables and Merkle DAGs
* Explain the relationship between block chains and Merkle DAGs

## Activities

1. **[Learn how Bit Torrent uses Hash Tables to Replicate Files](/decentralized-web-primer/presentations/How Bit Torrent Replicates Files)**: How bit torrent uses hash tables to replicate files
while maintaining data integrity
2. *TODO*: _Hash Trees (Merkle DAGs), Hash Tables and DHTs_ By default, Bit Torrent uses a Distributed Hash Table, not Hash Trees (Merkle DAGs). What's the difference? When does it matter?
2. **[Build a DAG with Git](build-a-dag-with-git)**
3. **[Use git to track changes and switch between versions of files](build-a-dag-with-git)**
5. *TODO*: _Replicating ledgers as Blockchains_: How blockchain technologies like bitCoin and ethereum use Merkle DAGs to distribute ledgers of transactions.  

## Bonus:

1. *TODO*: Build a DAG with hypercore and share it over a P2P network
2. **[Learn how hyperdrive tracks changes to files](/decentralized-web-primer/presentations/How Hyperdrive Replicates Changes to Files)**: How hyperdrive Uses Merkle DAGs to Replicate Files that Change Over Time  


Misc:

**[Git commits, trees and blobs](/decentralized-web-primer/presentations/How Git Stores Data)**: How Git Uses Merkle DAGs to represent files, directories, and the history of changes to that those files & directories.

## Contributors

Original Author: [flyingzumwalt](http://flyingzumwalt.com)
