---
blogpost: true
date: 2024-12-05
category: Talk
tags: [dask, xarray, performance, scalability]
author: Hendrik Makait
excerpt: 2
---
# Talk: Dask ❤️ Xarray: Geoscience at Massive Scale | PyData Global 2024

:::{video} https://www.youtube.com/watch?v=KJxJRx7KQtc
:::

## Abstract

**Doing geoscience is hard. It’s even harder if you have to figure out how to handle large amounts of data!**


Xarray is an open-source Python library designed to simplify the handling of labeled multi-dimensional arrays, like raster geospatial data, making it a favorite among geoscientists.
It allows these scientists to easily express their computations, and is backed by Dask, a Python library for parallel and distributed computing, to scale computations to entire clusters of machines.

People love using Xarray on Dask for geospatial workloads, but only up to about the terabyte scale.
At this point, the stack can struggle, requiring expertise to work well and frustrating users and developers alike.

To address this and enable the Dask ❤️ Xarray stack to scale to hundreds of terabytes, we have recently designed a suite of large-scale geospatial benchmarks.
With the help of these benchmarks, we are able to understand what limits performance within Dask and Xarray, and to address these issues.
In this talk, we will explore how Dask integrates with libraries like Xarray and Zarr to scale geospatial workloads and other multi-dimensional array computations.

We will also dive deeper into some of the bottlenecks in the Dask ❤️ Xarray stack that our benchmarks revealed, as well as some of the recent improvements we have made in these areas.
With the help of our benchmark suite, we then assess the impact of these changes.

Join us to discover how Dask helps you scale geoscience workloads from your laptop to the cloud.
