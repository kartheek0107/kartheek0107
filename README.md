<div align="center">

# Kartheek Budime

### **Systems & Backend Engineer**

Building high-performance, low-latency distributed systems and diving into infrastructure internals.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kartheek-budime)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kartheekbudime@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@kartheekbudime)

</div>

---

## ⚡ Core Engineering Philosophy

I build software with a focus on deep technical precision, zero-cost abstractions, and sub-millisecond efficiency. I prefer building from scratch to truly understand internal mechanisms, specializing in network protocols, concurrency models, and resource optimization.

---

## 🚀 Key Projects

### 🛠️ **GoDis** | *In-Memory Key-Value Store*
> A high-performance, production-ready Redis implementation written from scratch in Go.

*   **Architecture:** Implemented full custom **RESP protocol** parsing, thread-safe concurrent map structures, and **LRU eviction** algorithms.
*   **Reliability:** Engineered **AOF (Append-Only File) persistence** to guarantee data durability across restarts.
*   **Performance:** Benchmarked at **50K+ ops/sec** with sub-millisecond latency under a load of 10K+ concurrent connections via highly optimized Goroutine worker pools.
*   **Stack:** `Go` • `TCP` • `Goroutines` • `Network Programming`

[👉 View Repository](https://github.com/kartheek0107/godis)

### ⛓️ **Distributed Task Orchestrator**
> A fault-tolerant, high-throughput job scheduler designed for distributed environments.

*   **Design:** Built a platform-agnostic worker-pooling model utilizing **gRPC** for low-overhead, strongly-typed internal communication.
*   **Consistancy:** Integrated the **Redlock algorithm** for robust distributed locking, preventing race conditions across decoupled workers.
*   **Resilience:** Features proactive failure detection, automated state recovery, and self-service APIs.
*   **Stack:** `Go` • `Redis` • `gRPC` • `Docker` • `Protobuf`

### 📱 **Offline-First Mobile Data Layer**
> A cross-platform, deterministic sync engine optimizing local-first architectures.

*   **Implementation:** Developed a type-safe relational operation model using **SQLDelight** to guarantee compile-time query safety.
*   **Optimization:** Maximized mobile memory performance and disk I/O through meticulous column indexing and query tuning.
*   **Stack:** `Kotlin Multiplatform (KMP)` • `SQLite` • `SQLDelight`

### 📍 **Real-Time Delivery Coordination Platform**
> High-frequency, event-driven spatial tracking and messaging hub.

*   **Capabilities:** Processes low-latency **5-second location updates** with real-time geofencing and multi-user synchronization.
*   **Stack:** `FastAPI` • `PostgreSQL` • `Firebase Cloud Messaging (FCM)` • `React`

---

## 💼 Professional Experience

#### **Software Engineer Intern** • *Glexica* 
_September 2025 – January 2026_
*   Architected mission-critical backend APIs and streaming data pipelines.
*   Optimized database query paths and payload structures, driving a **40% reduction in system latency**.

#### **Web Solutions Intern** • *GlobalLogic* 
_May 2025 – July 2025_
*   Developed automated internal infrastructure tooling to optimize deployment pipelines.
*   Maintained infrastructure reaching **99.9% uptime** and accelerated CI/CD iteration cycles by **15%**.

---

## 🛠️ Technical Ecosystem

| Category | Technologies |
| :--- | :--- |
| **Languages** | `Go` • `C++` • `Python` • `Kotlin` • `Java` • `SQL` |
| **Infrastructure & Backend** | `Redis` • `PostgreSQL` • `Apache Kafka` • `gRPC` • `FastAPI` • `TCP/IP` |
| **DevOps & Systems** | `Docker` • `Kubernetes` • `Linux (Fedora)` • `Git` • `CI/CD Pipelines` |

---

## 📚 Technical Pursuits & Research Internals

I am constantly diving deeper into systems engineering primitives. Right now, I'm focusing on:
*   **Distributed Consensus:** Deconstructing the inner workings of `Raft` and `Paxos`.
*   **Storage Engines:** Analyzing database internals, specifically `LSM Trees` and `B+ Trees`.
*   **Cryptographic Protocols:** Exploring `Bitcoin Core` architecture and decentralized network layer development.

---

## 🎓 Education

*   **Indian Institute of Information Technology (IIIT), Sonepat**  
    *B.Tech in Computer Science and Engineering* (2023 — 2027)

---

<div align="center">

*“Building infrastructure that scales, one microsecond at a time.”*

</div>
