---
title: "Microservices Benchmarking Analysis"
description: "A framework for profiling and analyzing microservices performance in the DeathStarBench suite. Combines hardware counters, core-level profiling, and Jaeger tracing to identify bottlenecks, measure resource usage, and evaluate the impact of cache partitioning and CPU pinning."
date: "2025-02-01"
---

This repository provides a profiling and benchmarking framework for analyzing the performance of microservices in the DeathStarBench suite. It enables detailed service-level latency breakdowns by combining hardware performance counters, execution profiling, and distributed tracing (via Jaeger).

Key features:
 - Fine-grained analysis of core-level metrics (LLC loads/misses, instructions retired)
 - Support for containerized deployments via Docker Compose
 - Thread-to-core pinning and cache partitioning (Intel CAT) for isolation and resource control
 - Integration with Jaeger to collect, filter, and analyze traces from specific microservices
 - Automated multi-run test configuration for robust analysis

This tool is useful for systems researchers and engineers aiming to:
 - Evaluate microservice performance bottlenecks under realistic load
 - Study the impact of hardware-level resource contention
 - Optimize CPU/cache allocation strategies in containerized environments