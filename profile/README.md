<p align="center">
  <img src="spineldb-logo.png" alt="SpinelDB Logo" width="180"/>
</p>

<h1 align="center">Welcome to the SpinelDB Organization!</h1>

<p align="center">
  The official home of <strong>SpinelDB</strong> — a modern in-memory database built for the next generation of applications.
  <br />
  <br />
  <strong>Fast. Safe. Intelligent.</strong> 🦀 ⚡️ 💎
</p>

---

## 🎯 Our Mission

SpinelDB is an open-source project dedicated to building a next-generation in-memory database that serves as a powerful, reliable, and feature-rich alternative to traditional solutions. We believe in combining the raw performance and **memory safety of Rust** with a sophisticated feature set, including an **integrated intelligent caching engine**, to empower developers to build faster and more resilient systems.

Our goal is to create a database that is not only blazingly fast but also observable, secure, and ready for high-availability deployments.

## ✨ Core Project: SpinelDB Server

Our flagship project is the SpinelDB server, an all-in-one solution for your data storage and caching needs.

➡️ **Explore the main repository: [github.com/spineldb/spineldb](https://github.com/spineldb/spineldb)**

### Key Highlights:

*   **🚀 Redis-Compatible Core:** Designed for a high degree of compatibility with the Redis command API, allowing you to use your favorite clients and tools.
*   **🧠 Intelligent Caching Engine:** A first-class citizen in SpinelDB. Go beyond simple key-value caching with:
    *   `Stale-While-Revalidate` and `Grace TTL` for maximum performance and availability.
    *   On-disk streaming for caching large objects without exhausting memory.
    *   Tag-based purging (`CACHE.PURGETAG`) for instant, granular cache invalidation.
    *   Declarative policies to automate caching workflows based on key patterns.
*   **🛡️ Built for High Availability:**
    *   **Cluster Mode:** A multi-primary setup using a gossip protocol for node discovery and state propagation.
    *   **Warden:** An external monitoring process that provides robust, quorum-based automated failover, ensuring data safety and preventing split-brain scenarios.
*   **🦀 Written in Rust:** We leverage the full power of Rust and the Tokio ecosystem to deliver:
    *   **Fearless Concurrency:** A sharded, multi-threaded architecture that minimizes lock contention.
    *   **Memory Safety:** Elimination of entire classes of common bugs at compile time.
    *   **Exceptional Performance:** Asynchronous I/O for handling thousands of connections with minimal overhead.
*   **🧰 Rich Feature Set:** Includes robust persistence (AOF/SPLDB), Lua scripting, fine-grained Access Control Lists (ACLs), Pub/Sub, and advanced data structures like Streams and JSON.

## 💻 Our Technology Stack

We proudly build on some of the best technologies the open-source world has to offer:

*   **Language:** Rust 🦀
*   **Asynchronous Runtime:** Tokio 💨
*   **Concurrency:** DashMap, Parking Lot
*   **Observability:** Prometheus 📊, Tracing
*   **Cluster Communication:** Gossip Protocol 📡

## ❤️ Get Involved!

SpinelDB is a community-driven project, and we welcome contributions of all kinds. Whether you are a seasoned database engineer or a developer passionate about Rust, there are many ways to help.

*   **⭐ Star our main repository** to show your support!
*   **💻 Contribute Code:** Check out our [open issues](https://github.com/spineldb/spineldb/issues) to find a good starting point. Pull requests are always welcome.
*   **🐞 Report Bugs:** If you find a bug, please create a detailed issue.
*   **💡 Request Features:** Have an idea for a new command or a cool feature? Let's discuss it in the issues.
*   **✍️ Improve Documentation:** Help us make our documentation clearer and more comprehensive.
*   **📣 Spread the Word:** Tell your friends and colleagues about SpinelDB!

## 🌐 Community

*   **💬 Discussions:** Join the conversation in our [GitHub Discussions](https://github.com/spineldb/spineldb/discussions).
*   **Follow us on X (Twitter):** (Coming Soon!)
*   **Join our Discord/Slack:** (Coming Soon!)

---

<p align="center">
  Let's build the future of in-memory data storage, together.
</p>
