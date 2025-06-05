# Remote FUSE File System Backed by a Custom Key-Value Store

This project implements:
1. A semaphore-guarded, B-tree key-value engine in C
2. A multithreaded TCP server exposing a simple protocol
3. A FUSE client that mounts the remote store as a POSIX file system
4. Predictive prefetching and per-file lease locking (later milestones)

## Build

```bash
make                # after Week 1 Day 4
