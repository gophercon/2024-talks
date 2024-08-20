# Building a High-Performance Concurrent Map in Go - Yun Hao Zhang, ByteDance

## Talk Description

This talk will introduce how to design a concurrent map suitable for high-concurrency scenarios, as well as the problems existing in the `sync.Map` and built-in maps based on `sync.RWMutex` in high-concurrency scenarios. With this design, we can achieve an implementation that can be at least 10 times faster than `sync.Map` in typical cases (1% Delete, 9% Store, 90% Load).

## Speaker Info

YunHao Zhang (张云浩) is a software engineer on the ByteDance programming language team and a contributor to the Go standard library and runtime. He has more than five years of experience in Go language performance optimization. His recent research includes high-performance (concurrent) data structures and algorithms, programming language runtime, and the standard library (Go and Rust).

Blog: [github.com/zhangyunhao116](https://github.com/zhangyunhao116)

## Supporting Material

A PDF version of the slides from this talk are available [here](./YunHao%20Zhang%20-%20Building%20a%20High-Performance%20Concurrent%20Map%20in%20Go.pdf)
