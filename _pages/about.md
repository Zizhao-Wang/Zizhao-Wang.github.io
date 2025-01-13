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

<div style="display: flex; align-items: center; margin-bottom: 30px;">
    <img src="../images/figure1.png" alt="Data-driven Database Tuning" style="width: 40%; margin-right: 20px; border-radius: 8px;">
    <div>
        <h3>Data-driven Database Tuning</h3>
        <p>Utilizing stochastic planning, machine learning (ML), or LLM to dynamically tune data structures (e.g., B<sup>+</sup>-trees, LSM-trees) in response to varying workload patterns, ensuring optimal performance across diverse read/write scenarios.</p>
    </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 30px;">
    <div style="margin-right: 20px;">
        <h3>NoSQL Data Management Systems</h3>
        <p>Focusing on optimizing the storage layer of NoSQL databases, including Key-Value (KV) stores, Graph databases (DBs), and Document DBs, while developing new data structures (e.g., new LSM-like data structures) to improve read/write performance and scalability. <a href="#vldb2025">LuMDB</a>.</p>
    </div>
    <img src="../images/figure1.png" alt="NoSQL Data Management Systems" style="width: 40%; border-radius: 8px;">
</div>

<div style="display: flex; align-items: center; margin-bottom: 30px;">
    <img src="../images/figure1.png" alt="Modern Hardware Acceleration" style="width: 40%; margin-right: 20px; border-radius: 8px;">
    <div>
        <h3>Modern Hardware Acceleration</h3>
        <p>Focusing on leveraging (not based) cutting-edge hardware technologies, such as NVMe SSDs, persistent memory (PM), and Zone-namespace (ZNS) SSDs, while enhancing performance in two key areas:</p>
        <ul>
            <li><b>File System Expansion</b>: Expanding the capabilities of current general file systems (e.g., EXT4) to support better high-performance applications (e.g., KV stores, RDBs).</li>
            <li><b>Native Storage-Level Optimization</b>: Implementing application-specific (e.g., KV store) optimizations directly on native storage. Read more in <a href="#wise2024">REXIO</a>.</li>
        </ul>
    </div>
</div>

Selected Publications
======

**2024**

1.  <a name="wise2024"></a> "REXIO: Indexing for Low Write Amplification by Reducing Extra I/Os in Key-Value Store under Mixed Read/Write Workloads", **Zizhao Wang**,Jintao Meng<sup>*</sup>,Nan Han,Zhelang Deng,Yizhuo Ma,Xiaowen Huang, International Web Information Systems Engineering conference, main Track (WISE main), 2024. [PDF](../conference_pdfs/REXIO.pdf) [Code](https://github.com/Zizhao-Wang/REXIO)
1.  <a name="vldb2025"></a> "Low Unleashes More: Separating low-Access Data for Optimal Read/Write in LSM-based Key-Value Stores", **Zizhao Wang**,Yunjue Gu,Wenhan Feng,Jintao Meng,Yang Wang,André Brinkmann, 2024. [PDF](#) [Code](https://github.com/Zizhao-Wang/LuMDB)