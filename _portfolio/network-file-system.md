---
title: "Network File System Server (C++)"
collection: portfolio
permalink: /portfolio/network-file-system/
date: 2025-12-01
excerpt: "A multithreaded networked file system server with hierarchical directories, block-based ops, and strong consistency under concurrency."
tags: [C++, Systems, Networking, Concurrency]
---

Implemented a **multithreaded, networked file system server** in C++ that supports concurrent client access to a hierarchical directory structure and block-based file operations, with careful synchronization for correctness.

**Highlights**
- TCP server architecture with concurrent request handling (thread-per-connection)
- Hierarchical directories + ownership/permission checks
- Concurrency strategy emphasizing safe parallelism during path traversal and updates

**Links**
- GitHub Repo: https://github.com/oaydas/Network-File-System
