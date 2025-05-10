# TARTEQ OS & Networking Fundamentals

> *Under the hood of every system lies two pillars: the operating system and the network.*

This repository is a part of the **TARTEQ series** — focused on mastering core CS fundamentals that power every system and interview discussion.

Whether you're preparing for a system design round, backend engineering role, or simply sharpening your low-level understanding, this repo brings together crisp notes, real-world analogies, and interview-ready insights on **Operating Systems** and **Computer Networking**.

---

## 📚 Sections

### 🧠 Operating Systems
Concepts that control how your machine thinks, manages, and allocates:

- Processes vs Threads
- CPU Scheduling (FCFS, SJF, Round Robin, Priority)
- Memory Management (Paging, Segmentation, Virtual Memory)
- Deadlocks (Detection, Avoidance, Prevention)
- Synchronization (Mutex, Semaphore, Race Conditions)
- OS Interview Scenarios & Diagrams

### 🌐 Networking
Everything from packet transmission to user experience across the web:

- OSI Model vs TCP/IP Model
- TCP vs UDP (Reliability vs Speed)
- DNS, HTTP vs HTTPS
- 3-Way TCP Handshake, TLS Handshake
- Sockets vs REST vs WebSockets
- Load Balancing, CDNs, Latency vs Throughput
- Networking Interview Questions

### 🔄 System Design Crossovers
Where OS + Networking meet real-world architecture:

- Caching layers and CDN in web infra
- How OS threads impact backend throughput
- TCP tuning for scalable servers
- Failover, retries, heartbeat signals

---

## 🗂️ Folder Structure

```bash
tarteq-os-networking/
├── README.md
├── operating-systems/
│   ├── processes-vs-threads.md
│   ├── memory-management.md
│   ├── scheduling-algorithms.md
│   ├── synchronization.md
│   └── os-interview.md
├── networking/
│   ├── osi-tcp-model.md
│   ├── tcp-udp.md
│   ├── dns-http.md
│   ├── socket-vs-rest.md
│   └── network-interview.md
├── system-infra-crossovers/
│   ├── cdn-caching.md
│   ├── load-balancer.md
│   └── network-in-system-design.md