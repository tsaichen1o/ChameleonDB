# ChameleonDB
A high-performance, in-memory SQL-like database in modern C++ featuring a workload-adaptive indexing system.

ChameleonDB is a SQL-like in-memory database built from scratch in modern C++ (C++20/23). This repository is the final project for the "Introduction to C++ Programming" course at the Technical University of Munich (TUM).

The core feature of ChameleonDB is its advanced query performance optimization. It implements a workload-adaptive indexing mechanism inspired by the [SIGMOD '22 paper, "Adaptive Hybrid Indexes"](https://dl.acm.org/doi/pdf/10.1145/3514221.3526121). This allows the database to dynamically monitor query patterns and adjust its internal index structures in real-time, migrating data between performance-optimized and memory-efficient formats to achieve an optimal trade-off between speed and memory usage.
