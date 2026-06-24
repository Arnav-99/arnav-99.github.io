---
layout: page
title: Optimizing Compiler for C0 in Rust
description: Deliverable for Compiler Design (15-411), S25
importance: 2
category: academic
---

# Collaborators

Stephen Mao

# Languages Involved

- Implementation: Rust 
- Source: [C0](https://bitbucket.org/c0-lang/docs/wiki/Home), a safe subset of C
- Target: x86 ASM

# Optimizations

Aggressive Dead Code Elimination, Sparse Conditional Constant Propagation, Lazy Code Motion, Partial Redundancy Elimination, etc. 