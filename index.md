---
layout: index
title: Home
---

I am a final year PhD student at the University of Waterloo, working with Professor [Ali Mashtizadeh](https://rcs.uwaterloo.ca/~ali). My research is on operating systems, file systems, and cloud computing infrastructure. During my PhD I have used kernel mechanisms to provide efficient persistence, fault tolerance, and autoscaling to applications as an OS service. As of 2024 I am looking for industry engineering or research roles.

I obtained my undergraduate degree from the [National Technical University of Athens (NTUA)](https://www.ntua.gr/en), where I conducted research at the [Computing Systems lab](research.cslab.ece.ntua.gr). My undergraduate thesis was on utmem, an API that uses paravirtualization to expose a transcendent memory mechanism from the host directly to a guest Linux VM's applications.

# Projects

**Aurora**

The [Aurora](https://rcs.uwaterloo.ca/aurora/) project builds a fully UNIX compatible Single Level Store. Aurora's design goal is to transparently persist applications without developer effort. It does so by continuously checkpointing them and flushing these checkpoints to the disk. Aurora uses fast storage devices to do these checkpoints at a high frequency for fine grained persistence. 

**Persist-API**

This project is an explicit high-performance persistence API that applications use to efficiently persist memory-mapped data. Persist-API overcomes the correctness and scalability issues of existing OS APIs when used with memory-mapped data, and lets developers write simpler persistence code. Replacing the file API with Persist-API results in performance improvements for databases like RocksDB, SQLite, and PostgreSQL.

**Metropolis**

Metropolis optimizes Aurora's restore path for fast serverless function invocations. Metropolis creates function instances out of snapshot images with latency ranging from 500μs to 3ms and supports multiple languages, including Python, Ruby, and JavaScript. Metropolis also minimizes function memory usage by safely sharing individual dependencies between functions on a per-library granularity.


# Education

**PhD Degree**

University of Waterloo (2018-June 2024) <br/>
Advisor: [Ali José Mashtizadeh](https://rcs.uwaterloo.ca/~ali) <br/>
GPA: 92% <br/>
Topic: Transparent OS Persistence for Applications<br/>


**Undergraduate Degree**

National Technical University of Athens (2012-2018) <br/>
Advisor: [Georgios Goumas](https://www.cslab.ece.ntua.gr/~goumas) <br/>
GPA: 86% <br/>
Topic: Memory Elasticity for Virtual Machines with Trancendent Memory


## Conference Papers

*  [Ryan Hancock](https://rcs.uwaterloo.ca/~ryan), **Emil Tsalapatis**, [Ali José Mashtizadeh](https://rcs.uwaterloo.ca/~ali), [Omid Abari](https://web.cs.ucla.edu/~omid), [Yousra Aafer](https://cs.uwaterloo.ca/~yaafer). (Title anonymized) Fine-grained System Call Debloating for Secure OS Containers. Under submission.

*  **Emil Tsalapatis**\*, [Ryan Hancock\*](https://rcs.uwaterloo.ca/~ryan), [Rakeeb Hossain](https://rakeeb-hossain.github.io), [Ali José Mashtizadeh](https://rcs.uwaterloo.ca/~ali). MemSnap: A Data Single Level Store for Fearless Persistence. In Proceedings of the 29th ACM International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS '24). April, 2024. Acceptance Rate 19.8% (81/409)

* **Emil Tsalapatis**, [Ryan Hancock](https://rcs.uwaterloo.ca/~ryan), [Tavian Barnes](https://tavianator.com), [Ali José Mashtizadeh](https://rcs.uwaterloo.ca/~ali). [The Aurora Single Level Store Operating System](/assets/pdf/aurora-sosp.pdf). In Proceedings of the Symposium on Operating System Principles (SOSP '21). October, 2021. Acceptance Rate 15.6% (54/348)

## Workshops

* Stefanie Dukovac, **Emil Tsalapatis**, [Ali José Mashtizadeh](https://rcs.uwaterloo.ca/~ali). [SEEDS: Secure Extensible Enclave with Decentralized Storage for Secrets](/assets/pdf/seeds-systex.pdf).

* **Emil Tsalapatis**, [Ryan Hancock](https://rcs.uwaterloo.ca/~ryan), [Tavian Barnes](https://tavianator.com), [Ali José Mashtizadeh](https://rcs.uwaterloo.ca/~ali). [The Aurora Operating System: Revisiting the Single Level Store](/assets/pdf/aurora-hotos.pdf). In Proceedings of the Workshop on Hot Topics in Operating Systems (HotOS '21). June, 2021. Acceptance Rate 26.5% (30/113)

* **Aimilios Tsalapatis**, [Stefanos Gerangelos](http://www.cslab.ece.ntua.gr/~sgerag), Stratos Psomadakis, Konstantinos Papazafeiropoulos, [Nectarios Kozyris](http://www.cslab.ece.ntua.gr/~nkoziris). [utmem: Towards Memory Elasticity in Cloud Workloads](/assets/pdf/utmem.pdf).
In International Conference on High Performance Computing. June, 2018.

# Curriculum Vitae

Here is an up-to-date [resume](assets/pdf/tsalapatis_cv.pdf).

# Contact 

You can find me on [Github](https://github.com/etsal) and [LinkedIn](https://www.linkedin.com/in/emil-tsalapatis-41ab40b1).

You can contact me at *firstname* at *etsalapatis.com*.
