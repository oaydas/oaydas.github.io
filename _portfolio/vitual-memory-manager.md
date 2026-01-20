---
title: "Virtual Memory Manager (Pager) (C++)"
collection: portfolio
permalink: /portfolio/virtual-memory-manager/
date: 2025-11-01
excerpt: "A user-level virtual memory pager handling page faults, swap/file-backed pages, copy-on-write, and clock replacement."
tags: [C++, Systems, Operating Systems, Memory]
---

Built a **user-level virtual memory pager** in C++ to manage per-process address spaces and handle page faults, coordinating **physical memory**, **swap-backed pages**, and **file-backed mappings**.

**Highlights**
- Demand paging + page fault handling
- Copy-on-write semantics for swap-backed pages
- Clock (second-chance) page replacement under memory pressure
- Shared file-backed mappings with realistic VM semantics and resource accounting

**Links**
- GitHub Repo: https://github.com/oaydas/Virtual-Memory-Manager
