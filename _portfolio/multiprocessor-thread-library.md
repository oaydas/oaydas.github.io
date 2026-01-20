---
title: "Multiprocessor Thread Library (C++)"
collection: portfolio
permalink: /portfolio/multiprocessor-thread-library/
date: 2025-10-01
excerpt: "A preemptive, multiprocessor user-level thread library with kernel-style scheduling, IPIs, and synchronization primitives."
tags: [C++, Systems, Concurrency, Operating Systems]
---

Built a **preemptive, multiprocessor user-level thread library** in C++ that supports kernel-style scheduling across simulated CPUs, including **timer-driven preemption**, **inter-processor interrupts (IPIs)**, and core synchronization primitives (**threads, mutexes, condition variables**).

**Highlights**
- Multi-CPU scheduling with safe context switching (`ucontext`)
- Strict synchronization semantics under heavy concurrency
- FIFO-style coordination for blocking, waking, and ready-queue behavior

**Links**
- GitHub Repo: https://github.com/oaydas/Multiprocessor-Thread-Library
