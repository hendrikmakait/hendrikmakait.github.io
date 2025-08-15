---
blogpost: true
date: 2025-04-09
category: Talk
tags: [dask, xarray, scalability, performance]
author: Hendrik Makait
excerpt: 2
---
# Talk: Dask Array: Scaling Up for Terabyte-Level Performance | Pangeo Showcase 2025-04-09

:::{video} https://www.youtube.com/watch?v=p_D3W4C5ldg
:::

## Abstract

Dask Array is the distributed array framework that has been the de-facto standard for running large-scale Xarray computations for many years.
Nonetheless, the experience has been mixed. Over the last couple of months, Dask and Xarray maintainers have worked together to improve several shortcomings that have made workloads painful to run (or fail altogether) in the past.
In this talk, we will look at some of the improvements that were made, and how they combine with other changes like P2P rechunking to make running array computations at the Terabyte scale effortless.
