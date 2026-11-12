<h1 align="center">Hi, I'm Shaurya Jain 👋</h1>

<h3 align="center">Software Engineer | Systems Programming | Open Source</h3>

<p align="center">
  Building software, exploring systems from the ground up, and contributing to open-source projects.
</p>

<p align="center">
  <a href="https://github.com/tyrobro">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="YOUR_LINKEDIN_URL">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:YOUR_EMAIL_ADDRESS">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## About Me

I'm a Computer Science junior at **BITS Goa**, interested in building reliable, efficient software and understanding how systems work under the hood.

My work spans systems programming, distributed infrastructure, backend engineering, and performance-oriented software. I enjoy taking ideas from scratch, exploring architectural trade-offs, measuring performance, and turning technical concepts into working implementations.

Alongside my own projects, I actively explore established codebases and contribute to open-source software, particularly where I can improve functionality, reliability, or the developer experience.

- 🎓 **Education:** B.E. (Hons.) Computer Science, BITS — Expected 2028
- ⚙️ **Primary interests:** Systems programming, distributed systems, networking, and storage
- 🔧 **Engineering approach:** Build, benchmark, test, understand, and iterate
- 🌐 **Open source:** Interested in contributing to infrastructure, developer tools, and systems software

---

## Featured Projects

A selection of projects I've built, focused on systems engineering, performance, and distributed infrastructure.

### [Hermes](https://github.com/tyrobro)

**Lock-free HFT execution engine**

`C++` `CMake` `Concurrency` `Google Benchmark`

- Built a low-latency execution engine focused on minimizing tick-to-trade latency.
- Implemented a cache-optimized SPSC ring buffer for efficient inter-thread communication.
- Benchmarked four concurrency designs using Google Benchmark and CPU cycle measurements with `rdtsc`.
- Achieved **44 ns median tick-to-trade latency** and **32.4 million ticks per second** in project benchmarks.

### [Nyx](https://github.com/tyrobro)

**Serverless peer-to-peer communication mesh**

`Rust` `libp2p` `QUIC` `GossipSub` `AES-256-GCM`

- Built a peer-to-peer mesh designed for communication without relying on a central application server.
- Implemented NAT traversal using relay mechanisms and DCUtR.
- Added encrypted communication rooms using AES-256-GCM, with sensitive data handling through Zeroize.
- Integrated Kademlia DHT for peer discovery and lookup.
- Implemented token-bucket rate limiting to help control network traffic.

### [Heimdall](https://github.com/tyrobro)

**Distributed storage engine**

`Go` `Python` `gRPC` `BoltDB` `Prometheus`

- Built a distributed storage engine with a focus on persistence, consistency, and recovery.
- Implemented a write-ahead log, multi-version concurrency control (MVCC), and crash recovery.
- Added LRU-based caching and performance instrumentation.
- Achieved up to **270× faster ingestion** compared with synchronous BoltDB writes in project benchmarks.

---

## Open-Source Contributions

I enjoy working with established codebases, understanding their architecture, and contributing improvements that make software more reliable and easier to use.

### [Apache Druid — PR #20818](https://github.com/apache/druid/pull/20818) · Merged

**Fix flaky embedded compaction tests**

`Java` `Testing` `Apache Druid`

- Fixed a flaky test timeout in `CompactionTestBase.createCluster()`.
- Increased the default `LatchableEmitter` timeout from 10 seconds to 60 seconds.
- Addressed failures occurring when compaction tasks took longer than expected to emit `task/run/time` events on loaded CI runners.
- Aligned the configuration with the existing approach used in `StreamIndexTestBase`.

### [Axl / Observal — PR #440](https://github.com/Observal/Axl/pull/440) · Merged

**Command suggestion improvements**

`Go` `Levenshtein Distance` `Testing`

- Implemented a `closestMatch` helper using Levenshtein edit distance to suggest the closest matching slash command or theme when users enter a typo.
- Integrated suggestions into two TUI error-handling paths.
- Added 10 tests covering the matching behaviour.
- Worked through five rounds of automated review feedback.

I am interested in contributing to systems software, developer tooling, infrastructure, and other projects where I can make practical engineering improvements.

---

## Professional Experience

### Software Engineering Intern — FoundershipHQ Accelerator Pvt. Ltd.

*May 2026 – July 2026*

**ExplaraX Check-in — Independent multi-gate check-in system**

`React` `Progressive Web Apps` `Supabase` `PostgreSQL` `AWS EC2`

- Built an independent Progressive Web App (PWA) check-in system designed to decouple live event check-in traffic from the core ticketing database.
- Developed a multi-gate check-in workflow with a React-based scanner and host dashboard.
- Used Supabase PostgreSQL, Realtime, and Edge Functions to support the check-in infrastructure.
- Implemented atomic, race-safe check-in logic to ensure concurrent QR scans produce a single definitive `ALLOWED` or `DENIED` result.
- Deployed the system on AWS EC2.
- Load-tested attendee search with **10,000 attendees** and check-in traffic at **50 scans per second across five gates**, achieving sub-500 ms search performance.

---

## Technical Skills

| Category | Technologies |
|---|---|
| **Languages** | C++, Rust, Go, Python, Java, JavaScript, TypeScript, SQL, Verilog |
| **Systems & Networking** | Concurrency, Lock-free Data Structures, QUIC, libp2p, GossipSub, gRPC |
| **Backend & Frameworks** | FastAPI, Node.js, React |
| **Databases & Storage** | PostgreSQL, BoltDB, MVCC, Write-Ahead Logging |
| **Infrastructure & Tools** | Git, CMake, Prometheus, AWS EC2 |
| **Engineering Practices** | Benchmarking, Performance Optimization, Testing, Distributed Systems |

---

## Areas of Interest

I'm particularly interested in exploring:

- **Systems Programming:** Operating systems, memory management, concurrency, and low-level performance.
- **Distributed Systems:** Fault tolerance, consistency, replication, and distributed storage.
- **Networking:** Peer-to-peer architectures, transport protocols, and network infrastructure.
- **Backend Engineering:** Scalable services, databases, and reliable infrastructure.
- **Open Source:** Understanding large codebases, collaborating with maintainers, and contributing meaningful improvements.

---

## GitHub Activity

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=tyrobro&show_icons=true&hide_border=true&theme=transparent"
    height="165"
    alt="GitHub statistics"
  />
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=tyrobro&layout=compact&hide_border=true&theme=transparent"
    height="165"
    alt="Most used programming languages"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-streak-stats.herokuapp.com/?user=tyrobro&hide_border=true&theme=transparent"
    alt="GitHub contribution streak"
  />
</p>

---

## Let's Connect

I'm always interested in discussing systems engineering, open-source software, distributed infrastructure, and interesting technical problems.

- **LinkedIn:** [YOUR LINKEDIN PROFILE]((https://www.linkedin.com/in/shauryajain76/))
- **Email:** [YOUR EMAIL ADDRESS](mailto:shaurya7jain@gmail.com)
- **GitHub:** [github.com/tyrobro](https://github.com/tyrobro)

---

<p align="center">
  <i>Building things, understanding how they work, and making them better.</i>
</p>
