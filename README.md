# database_internals
chinese translation of database internals, now the progress is

- [ ] Part 1 - Storage Engine
  - [x] Chapter 1 - Introduction and Overview
    - [x] DBMS Architecture
    - [x] Memory- Versus Disk-Based DBMS
    - [x] Column- Versus Row-Oriented DBMS
    - [x] Data Files and Index Files
    - [x] Buffering Immutablity and Ordering
    - [x] Summary
  - [x] Chapter 2 - BTree Basics
    - [x] Binary Search Trees
    - [x] Disk Based Structures
    - [x] Ubiquitous B-Trees
  - [x] Chapter 3 - FIle Format
    - [x] Motivation
    - [x] Binary Encoding
    - [x] General Principles
    - [x] Page Structure
    - [x] Slotted Pages
    - [x] Cell Layout
    - [x] Combining Cells into Slotted Pages
    - [x] Managing Variable-Size Data
    - [x] Versioning
    - [x] Checksumming
    - [x] Summary
  - [x] Chapter 4 - Implement B-Trees
    - [x] Page Header
    - [x] Binary Search
    - [x] Propagating Splits and Merges
    - [x] Rebalancing
    - [x] Right-Only Appends
    - [x] Compression
    - [x] Veccum and Maintenance
    - [x] Summary
  - [x] Chapter 5 - Transaction Processing and Recory
    - [x] Buffer Management
    - [x] Recovery
    - [x] Concurrency Control
    - [x] Summary
  - [ ] Chapter 6 - B-Tree Variants
    - [ ] Copy-on-Write
    - [ ] Abstracting Node Updates
    - [ ] Lazy B-Trees
    - [ ] FD-Trees
    - [ ] BW-Trees
    - [ ] Cache-Oblivious B-Trees
  - [ ] Chapter 7 - Log-Structured Storage
    - [ ] LSM Trees
    - [ ] Read, Write, and Space Amplification
    - [ ] Implemention Details
    - [ ] Unordered LSM Storage
    - [ ] Concurrency in LSM Trees
    - [ ] Log Stacking
    - [ ] LLAMA and Mindful Stacking
    - [ ] Summary
- [ ] Part 2 - Distributed Systems
