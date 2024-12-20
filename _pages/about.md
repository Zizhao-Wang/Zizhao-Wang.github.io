---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

---
I'm currently a third-year graduate student at the [ShenZhen Institute of Advanced Technology (SIAT)](https://english.siat.ac.cn/), affiliated with the [University of Chinese Academy of Sciences (UCAS)](https://english.ucas.ac.cn/). I am advised by [Prof. Meng Jintao](http://210.75.252.46/jintao/)and [Prof. Wang Yang](https://people.ucas.edu.cn/~yangwang) in SIAT. My primary research collaborations are with [Prof. Dr.-Ing. André Brinkmann](https://research.zdv.uni-mainz.de/people/andre-brinkmann/) at Johannes Gutenberg - Universität Mainz. Together, we have been working on a combination of computer systems and databases, especially for key-value store optimization.

**I am currently looking forward to a PhD position.**

Research Interests
======

- **Data-driven Database Tuning**: Utilizing stochastic planning, machine learning (ML), or LLM to dynamically tune data structures (e.g., B<sup>+</sup>-trees, LSM-trees) in response to varying workload patterns, ensuring optimal performance across the diverse read/write scenarios.

- **NoSQL Data Management Systems**: Focusing on optimizing the storage layer of NoSQL databases, including Key-Value (KV) stores, Graph databases (DBs), and Document DBs, while developing new data structures (e.g., new LSM-like data structures) to improve read/write performance and scalability. [LuMDB](#vldb2025).

- **Modern Hardware Acceleration**: Focusing on leveraging (not based) cutting-edge hardware technologies, such as NVMe SSDs, persistent memory (PM), and Zone-namespace (ZNS) SSDs, while enhancing performance in two key areas:
    - **File System Expansion**: Expanding the capabilities of current general file systems (e.g., EXT4) to support better high-performance applications (e.g., KV stores, RDBs).
    - **Native Storage-Level Optimization**: Implementing application-specific (e.eg., KV store) optimizations directly on native storage. Read more in [REXIO](#wise2024).

Selected Publications
======

**2024**

1.  <a name="wise2024"></a> "REXIO: Indexing for Low Write Amplification by Reducing Extra I/Os in Key-Value Store under Mixed Read/Write Workloads", **Zizhao Wang**,Jintao Meng<sup>*</sup>,Nan Han,Zhelang Deng,Yizhuo Ma,Xiaowen Huang, International Web Information Systems Engineering conference, main Track (WISE main), 2024. [PDF](../conference_pdfs/REXIO.pdf) [Code](https://github.com/Zizhao-Wang/REXIO)
1.  <a name="vldb2025"></a> "Low Unleashes More: Separating low-Access Data for Optimal Read/Write in LSM-based Key-Value Stores", **Zizhao Wang**,Yunjue Gu,Wenhan Feng,Jintao Meng,Yang Wang,André Brinkmann, 2024. [PDF](#) [Code](https://github.com/Zizhao-Wang/LuMDB)