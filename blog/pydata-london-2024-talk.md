---
blogpost: true
date: 2024-06-15
category: Talk
tags: [dask, observability, coiled, performance]
author: Hendrik Makait
excerpt: 2
---
# Observability for Dask in Production | Pydata London 2024

:::{video} https://www.youtube.com/watch?v=gHsT6gHSkWM
:::

## Abstract

**Debugging is hard. Distributed debugging is hell.**

Dask is a popular library for parallel and distributed computing in Python.
Dask is commonly used in data science, actual science, data engineering, and machine learning to distribute workloads onto clusters of many hundreds of workers with ease.

However, when things go wrong life can become difficult due to all of the moving parts.
These parts include your code, other PyData libraries like NumPy/pandas, the machines you’re running on, the network between them, storage, the cloud, and of course issues with Dask itself.
It can be difficult to understand what is going on, especially when things seem slower than they should be or fail unexpectedly.
Observability is the key to sanity and success.

In this talk, we describe the tools Dask offers to help you observe your distributed cluster, analyze performance, and monitor your cluster to react to unexpected changes quickly.
We will dive into distributed logging, automated metrics, event-based monitoring, and root-causing problems with diagnostic tooling.
Throughout the talk, we will leverage real-world use cases to show how these tools help to identify and solve problems for large-scale users in the wild.

This talk should be particularly insightful for Dask users, but the approaches to observing distributed systems should be relevant to anyone operating at scale in production.
