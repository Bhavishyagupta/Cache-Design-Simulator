# Cache-Design-Simulator
Designed and implemented a configurable L1 and L2 cache simulator in C++. The simulator models a realistic multi-level cache hierarchy with support for configurable cache size, associativity, and block size, using an LRU replacement policy and write-back, write-allocate (WBWA) write strategy.

The simulator processes memory access traces (read/write operations), accurately tracks cache hits, misses, write-backs, and memory traffic, and reports detailed performance statistics. The design cleanly separates cache functionality across hierarchy levels and supports extensibility for additional cache features. The project emphasizes architectural correctness, performance modeling, and clean, maintainable implementation using Makefile-based builds and modular headers.

Key highlights:
Multi-level cache hierarchy (L1 + L2)
LRU replacement policy with precise eviction handling
WBWA write policy and dirty block management
Trace-driven simulation with detailed statistics reporting
Modular C++ design with reproducible build flow
