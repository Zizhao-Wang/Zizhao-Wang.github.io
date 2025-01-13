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

<style>
    /* 通用容器样式 */
    .responsive-container {
        display: flex;
        align-items: center;
        margin-bottom: 30px;
    }

    .responsive-container img {
        width: 40%;
        margin-right: 20px;
        border-radius: 8px;
    }

    .responsive-container div {
        flex: 1;
    }

    /* 适配移动端：屏幕宽度小于768px时 */
    @media screen and (max-width: 768px) {
        .responsive-container {
            display: block; /* 单列布局 */
            text-align: center;
        }

        .responsive-container img {
            width: 80%; /* 图片宽度调整 */
            margin: 0 auto 20px auto; /* 居中显示 */
        }

        .responsive-container div {
            text-align: left; /* 保持文字左对齐 */
        }
    }
</style>

<div class="responsive-container">
    <img src="../images/figure1.png" alt="Data-driven Database Tuning">
    <div>
        <h3>Data-driven Database Tuning</h3>
        <p>Utilizing stochastic planning, machine learning (ML), or LLM to auto-tune data structures (e.g., B<sup>+</sup>-trees, LSM-trees) to ensure optimal performance across diverse read/write workloads.</p>
    </div>
</div>

<div class="responsive-container">
    <div>
        <h3>NoSQL Data Management Systems</h3>
        <p>Optimizing the NoSQL databases, including Key-Value (KV) stores, Graph databases (DBs), and Document DBs, while developing new structures (e.g., new LSM-like structures) to improve read/write performance and scalability. <a href="#vldb2025">LuMDB</a>.</p>
    </div>
    <img src="../images/figure2.png" alt="NoSQL Data Management Systems" >
</div>

<div class="responsive-container">
    <img src="../images/figure1.png" alt="Modern Hardware Acceleration">
    <div>
        <h3>Modern Hardware Acceleration</h3>
        <p> Leveraging (not based) cutting-edge hardwares, e.g., NVMe SSDs, persistent memory (PM), and Zone-namespace (ZNS) SSDs, to enhance performance in:</p>
        <ul>
            <li><b>File System Expansion</b>: Expanding the capabilities of file systems (e.g., EXT4) to support better high-performance apps (e.g., KV stores, RDBs).</li>
            <li><b>Native Storage Optimization</b>: Application-specific (e.g., KV store) optimizations on native storage. <a href="#wise2024">REXIO</a>.</li>
        </ul>
    </div>
</div>

Selected Publications
======

**2024**

1.  <a name="wise2024"></a> "REXIO: Indexing for Low Write Amplification by Reducing Extra I/Os in Key-Value Store under Mixed Read/Write Workloads", **Zizhao Wang**,Jintao Meng<sup>*</sup>,Nan Han,Zhelang Deng,Yizhuo Ma,Xiaowen Huang, International Web Information Systems Engineering conference, main Track (WISE main), 2024. [PDF](../conference_pdfs/REXIO.pdf) [Code](https://github.com/Zizhao-Wang/REXIO)
1.  <a name="vldb2025"></a> "Low Unleashes More: Separating low-Access Data for Optimal Read/Write in LSM-based Key-Value Stores", **Zizhao Wang**,Yunjue Gu,Wenhan Feng,Jintao Meng,Yang Wang,André Brinkmann, 2024. [PDF](#) [Code](https://github.com/Zizhao-Wang/LuMDB)