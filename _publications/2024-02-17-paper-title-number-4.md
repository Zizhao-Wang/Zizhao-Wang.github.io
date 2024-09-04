---
title: "REXIO: An Indexing for Low Write Amplification by Reducing Extra I/Os in Mixed Read/Write Workloads"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper proposed REXIO, an indexing mechanism for organizing key-value (KV) items in KV store to achieve lowest write amplification under read/write mixed workload.'
date: 2024-12-2
venue: 'International Web Information Systems Engineering conference (WISE)'
paperurl: ''
citation: ''
---
In mixed read/write workloads, Key-Value stores that utilize Log-Structured Merge (LSM) trees face significant write amplification problems due to frequent writing, resulting in extensive data compaction. While current LSM-based KV stores effectively address write amplification in write-heavy workloads, they struggle with increased block cache invalidation and increased read/write I/O conflicts in mixed read/write workloads. This paper introduces REXIO, a novel indexing approach to reduce write amplification. It decouples RAM from Solid State Drives (SSDs) and stores addresses of KV pairs in the In-RAM hashing table, which reduces buffer invalidations and eliminates unnecessary data reorganization to lower extra I/Os, thereby reducing I/O conflicts. Additionally, REXIO stores keys and values in different blocks and employs In-blocking logging to optimize updating and deleting. The experimental results show that REXIO achieves a 68.3% reduction of write amplification and 3.4x throughput compared to state-of-the-art LSM-Tree approaches.
