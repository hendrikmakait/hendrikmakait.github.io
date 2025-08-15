---
blogpost: true
date: 2024-09-24
category: Talk
tags: [dask, xarray, performance, scalability]
author: Hendrik Makait
excerpt: 1 
---
# Talk: Geoscience at Massive Scale | PyData Paris 2024

:::{video} https://www.youtube.com/watch?v=UOpNhItJNv8
:::

## Abstract

When scaling geoscience workloads to large datasets, many scientists and developers reach for Dask, a library for distributed computing that plugs seamlessly into Xarray and offers an Array API that wraps NumPy.
Featuring a distributed environment capable of running your workload on large clusters, Dask promises to make it easy to scale from prototyping on your laptop to analyzing petabyte-scale datasets.

Dask has been the de-facto standard for scaling geoscience, but it hasn’t entirely lived up to its promise of operating effortlessly at massive scale.
This comes up in a few ways:
* Correctly chunking your dataset has a significant impact on Dask’s ability to scale 
* Workers accidentally run out of memory due to: 
* Data being loaded too eagerly
* Rechunking
* Unmanaged memory

Over the last few months, Dask has addressed many of those pains and continues to do so through:
* Improvements to its scheduling algorithms
* A faster and more memory-stable method for rechunking
* First-of-its-kind logical optimization layer for a distributed array framework (ongoing)

Join us as we dive into real-world geoscience workloads, exploring how Dask empowers scientists and developers to run their analyses at massive scale.
Discover the impact of improvements made to Dask, ongoing challenges, and future plans for making it truly effortless to scale from your laptop to the cloud.
