---
permalink: /
title: "Zizhao-Wang's HomePage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

---
I'm currently a third-year graduate student from [ShenZhen Institute of Advanced Technology (SIAT)](https://english.siat.ac.cn/), affiliated with the [University of Chinese Academy of Sciences (UCAS)](https://english.ucas.ac.cn/). I am very fortunate to be advised by [Prof. Meng Jintao](http://210.75.252.46/jintao/) of [Center for High-Performance Computing](https://hpcc.siat.ac.cn/) and [Prof. Wang Yang](https://people.ucas.edu.cn/~yangwang) of [Center for Cloud Computing](http://cloud.siat.ac.cn/cloud/) from [Institute of Advanced Computing and Digital Engineering](http://english.siat.cas.cn/SI2017/IACDE2017/) in SIAT. Additionally, I am collaborating with [Prof. Dr.-Ing. André Brinkmann](https://research.zdv.uni-mainz.de/people/andre-brinkmann/) at Johannes Gutenberg - Universität Mainz.

**I am currently looking forward to a PhD position.**

Research Interests
======

- **Data-driven Database Tuning**: Utilizing stochastic planning, machine learning (ML), or LLM to dynamically tune data structures (e.g., B<sup>+</sup>-trees, LSM-trees) in response to varying workload patterns, ensuring optimal performance across the diverse read/write scenarios.

- **NoSQL Data Management Systems**: Focusing on optimizing the storage layer of NoSQL databases, including Key-Value (KV) stores, Graph databases (DBs), and Document DBs, while developing new data structures (e.g., new LSM-like data structures) to improve read/write performance and scalability. [LuMDB](#wise2024).

- **Modern Hardware Acceleration**: Focusing on leveraging (not based) cutting-edge hardware technologies, such as NVMe SSDs, persistent memory (PM), and Zone-namespace (ZNS) SSDs, while enhancing performance in two key areas:
    - **File System Expansion**: Expanding the capabilities of current general file systems (e.g., EXT4) to support better high-performance applications (e.g., KV stores, RDBs).
    - **Native Storage-Level Optimization**: Implementing application-specific (e.eg., KV store) optimizations directly on native storage. Read more in [WISE'24](#wise2024).

Latest News
======
- **August 2024** - Our paper titled "REXIO: An Indexing for Low Write Amplification by Reducing Extra I/Os in Mixed Read/Write Workloads" has been accepted by the International Web Information Systems Engineering conference (WISE 2024).


# Selected Publications

======

**2024**

1.  <a name="wise2024"></a> **[WISE'2024]** "REXIO: Indexing for Low Write Amplification by Reducing Extra I/Os in Key-Value Store under Mixed Read/Write Workloads", **Zizhao Wang**,Jintao Meng<sup>*</sup>,Nan Han,Zhelang Deng,Yizhuo Ma,Xiaowen Huang, International Web Information Systems Engineering conference, main Track (WISE main), 2024. [PDF](#) [Code](https://github.com/Zizhao-Wang/REXIO)
1.  <a name="wise2024"></a> "Low Unleashes More: Separating low-Access Data for Optimal Read/Write in LSM-based Key-Value Stores", **Zizhao Wang**, 2024. [PDF](#) [Code](https://github.com/Zizhao-Wang/LuMDB)